# Welcome to the JToHKitRewritten!

The JToHKitRewritten is a completely overhauled version of the JToH Kit. It takes advantage of optimizations to make things run much much faster while also allowing for more creative freedom.

* Works out of the box

    * No need to place scripts anywhere

* Embedded Client Objects

    * Client Objects can now be placed under any other Client Object or Server Object

* Support for multiple Towers

    * Includes the addition of a Portal along with Tower starting and ending functionality

* Custom scripting is encouraged

    * Create your own custom Tower functionality or Client Objects using the built-in modding framework

In this repository you will find detailed documentation on virtually everything contained in the Kit. Head to the docs folder to see more.  
<pre>
▿ 📁 JToHKitRewritten <sup><b>Tag:</b> <i>JToHKitRewritten</i></sup>
    ▿ 📁 Towers
        ▿ 📁 <i>[Insert Tower Name]</i> <sup><b>Tag:</b> <i>TowerFolder</i></sup>
            ▿ 📁 Frame
                ▿ 📁 Floor <i>[Insert Floor Number Here]</i>
                    ▫️ 🔶 Part
            ▿ 📁 Mods
                ▫️ 🟪 Default
                ▫️ 🟪 <i>[Insert Mod Name Here]</i>
            ▿ 📁 Workspace
                ▫️ 🔶 ServerObject
                ▫️ 🔷 ClientObject <sup><b>Tag:</b> <i>ClientObject</i></sup>
            ▿ 📚 Portal
                ▫️ 🔲 PortalTeleporter
            ▫️ 🔲 Start
            ▫️ 🔲 Winpad
    ▿ 📃 Main
        ▿ 📘 Client
            ▫️ 📘 ModHandler
            ▫️ 🟪 KitPlayer
            ▫️ 🟪 Tower
            ▫️ 🟪 Util
            ▫️ ⏹ JToHKitRewrittenGui
        ▫️ 🟪 Types
</pre>
<sup>
🔶 = ServerObject
</br>
🔷 = ClientObject
</br>
📚 = Model
</br>
🔲 = BasePart
</br>
📘 = ClientScript
</br>
🟪 = ModuleScript
</br>
⏹ = ScreenGui
</sup> 

</br>
If you have any issues or suggestions for the Kit or its documentation, feel free to submit a new Issue.
