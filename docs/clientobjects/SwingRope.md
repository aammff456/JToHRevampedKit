# SwingRope

A rope that can be swung on by the Player

## Structure
<pre>
▿ 🔲 SwingRope <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▫️ 🔹Attachment0
    ▫️ 🔹Attachment1
    ▫️ ➡️ RopeConstraint
    ▫️ ⚙️ GrabSound
    ▫️ ⚙️ JumpSound
</pre>

## When Disabled
<pre>
The rope cannot be swung on
</pre>

## Attributes
<pre>
<b>Cooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How long the SwingRope will remain inactive after being activated
</pre>

<pre>
<b>JumpOnDismount</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the Player automatically jumps when dismounted from the rope by external means
</pre>

<pre>
<b>ManualDismount</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the Player can manually dismount the rope by jumping
</pre>
