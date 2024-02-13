# Default Client Objects

Default Client Objects are the Client Objects that come built into the Kit. The scripts for these Objects are not located inside each Object, but are instead stored under the Default mod in the Tower Mod's Folder.

## Dynamic
The Default Client Objects are dynamic, meaning that most of their attributes can be changed on the fly through external means, and the internal state of the Object will be updated accordingly. For instance, you can manually toggle the 'Pressed' attribute to press a Button without having something touch it.

## Toggle Attribute
All of the Default Client Objects come with an 'Enabled' attribute that will toggle the functionality of the Object dynamically. For instance, a KillBrick can be disabled to prevent it from dealing damage to the Player.

## Overriding and Changing Functionality
If you want to modify the functionality of any Default Client Object type, it is recommended to do so in a separate Mod so the modifications are clear. You can simply set the 'Enabled' property of any specific Client Object script to false (or you can delete the script if you're sure you won't need it) and copy and paste the code somewhere else where it can be modified.

If you only want to modify a single Object, you can make a separate Client Object Type and make a script that targets its type specifically.
