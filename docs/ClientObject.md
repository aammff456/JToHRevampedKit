# Client Objects

Client Objects are objects in a Tower that can only be seen on the Client. They commonly employ some sort of special functionality that makes the Tower more interesting. Client Objects always need to take the following form:

<pre>
▿ 📁 <i>[Insert Tower Name]</i> <sup><b>Tag:</b> <i>TowerFolder</i></sup>
    ▿ 📁 Workspace
        ▫️ 🔷 ClientObject <sup><b>Tag:</b> <i>ClientObject</i></sup>
</pre>
<sup>* All Client Objects must have the "ClientObject" tag to be treated as one</sup>

All Client Objects are required to have a ClientObjectType attribute. This attribute is part of what makes the custom scripting framework possible. The type does not need to be anything in specific, but should represent what kind of Client Object something is.

The added benefit is that this frees up a Client Object's Name property, so you're free to name Client Objects whatever you want, just make sure the name makes sense.

## How Do Client Objects Work?

### Server-side
The Server gets a list of all objects tagged "ClientObject", which is a very fast operation thanks to CollectionService. It finds the Tower each Client Object is associated with by checking the Parent property until it finds a Folder with the tag "TowerFolder". While doing this, however, it can also detect if it is an Embedded Client Object (specifically when it is underneath another Client Object), and will mark it as such.

If the Client Object is not Embedded, the Server will take note of what its Parent is and move the Client Object into a Tower-designated Folder in ReplicatedStorage, where the Client can see it.

When a Player touches a Portal, it will send a message to their Client to start the Tower.

### Client-side 
When the Client receives this messsage, it will clone all of the Client Objects in ReplicatedStorage associated with that Tower and put them under their original Parents (this means that Client Objects can be placed under Server Objects too), and giving each of them a type-unique tag.

After all Client Objects have been loaded, the Client loads GUI and other things necessary for the Tower and tells the Server that it has finished loading. 

The Server will then teleport the Player into the Tower and wait for the Player to touch the Winpad, at which point all Client Objects will be unloaded.