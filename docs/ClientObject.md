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