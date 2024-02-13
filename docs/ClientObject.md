# Client Objects

Client Objects are objects in a Tower that can only be seen on the Client. They commonly employ some sort of special functionality that makes the Tower more interesting. Client Objects always need to take the following form:

<pre>
▿ 📁 <i>[Insert Tower Name]</i> <sup><b>Tag:</b> <i>TowerFolder</i></sup>
    ▿ 📁 Workspace
        ▫️ 🔷 ClientObject <sup><b>Tag:</b> <i>ClientObject</i></sup>
</pre>
<sup>* All Client Objects must have the "ClientObject" tag to be treated as one</sup>
<sup>* Client Objects don't have to be placed in the Tower Workspace, but in most cases are</sup>

All Client Objects are required to have a ClientObjectType attribute. This attribute is part of what makes the custom scripting framework possible. The type does not need to be anything in specific, but should represent what kind of Client Object something is.

The added benefit is that this frees up a Client Object's Name property, so you're free to name Client Objects whatever you want. However, the descendants of a Client Object may require specific naming (If this ends up being an issue you will get an error describing exactly what went wrong).

## How Do Client Objects Work?

### Server-side
The Server gets a list of all objects tagged "ClientObject", which is a very fast operation thanks to CollectionService. It finds the Tower each Client Object is associated with by checking the Parent property until it finds a Folder with the tag "TowerFolder". While doing this, however, it can also detect if it is an Embedded Client Object (when it is underneath another Client Object).

If the Client Object is not Embedded, the Server will take note of what its Parent is and move the Client Object into a Tower-designated Folder in ReplicatedStorage, where the Client can see it.

When a Player touches a Portal, it will send a message to their Client to start the Tower.

### Client-side 
When the Client receives this messsage, it will clone all of the Client Objects in ReplicatedStorage associated with that Tower and put them under their original Parents (this means that Client Objects can be placed under Server Objects too), and will give each of them a type-unique tag.

After all Client Objects have been loaded, the Client loads GUI and other things necessary for the Tower and tells the Server that it has finished loading. 

The Server will then teleport the Player into the Tower and wait for the Player to touch the Winpad, at which point all Client Objects will be unloaded.

## Replication Nuance

When dealing with Client-specific things, oftentimes the Server will replicate things we don't want replicated, or won't replicate things we do want replicated.

### Cross-Client Collision

Client Objects themselves will never replicate to the Server. However, Roblox utilizes a dynamic Physics system that can offload some of the calculations to a given Client (which can also make the Client experience smoother). This means that oftentimes, nearby Physics will end up replicating to the Server.

This is a problem because two Clients playing the same Tower can sometimes interfere with the other's Client Objects (for instance another Player could push your Pushbox without even being able to see it).

This is fixed by implementing collision groups, which prevent other Players from interacting with your own Client Objects.

### Health and Character CFrame Replication

If the health of a Player is changed on the Client, the Server will not perceive this change unless the Player dies. To fix this, when the Player's health changes, the Client sends this new health to the Server and it is updated accordingly. By ensuring the health is changed on the Client and merely updated on the Server, it removes the infamous "KillBrick Lag".

If you are a veteran JToH Player, you may be familiar with the fact that when you are spectating a Player and they are on a Zipline, they visibly freeze until they dismount. To fix this, the Client sends CFrame information to the Server so it can be seen by all Players. The same also applies when a Player sits in a seat.
