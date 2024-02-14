# BeatBlocks

A collection of platforms that toggle on and off in series

## Structure
<pre>
▿ 📁 BeatBlocks <sup><b>Tags:</b> <i>ClientObject, [ButtonDeactivator Groups]</i></sup>  
    ▫️ 🔲 1
    ▫️ 🔲 2
    ▫️ 🔲 3
    ▫️ 🔲 ...
</pre>

## When Disabled
<pre>
The BeatBlocks will freeze in the next stable state and will stop toggling
</pre>

## Attributes
<pre>
<b>EnabledTransparency</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Description:</b> Determines how long a platform takes to transition to its next state. This helps the player know when the platforms will toggle
</pre>

<pre>
<b>ToggleTime</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how long it takes for the next platform in the series to activate  
</pre>

<pre>
<b>TransitionTime</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how long a platform takes to transition to its next state. This helps the player know when the platforms will toggle. Setting this value to 0 will cause platforms to transition instantly
</pre>
