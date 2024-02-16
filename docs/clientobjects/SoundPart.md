# SoundPart

A Part that will play a sound when interacted with

## Structure
<pre>
▿ 🔲 SoundPart
    ▫️ ⚙️ Sound
</pre>

## When Disabled
<pre>
Will not play sound
</pre>

## Attributes
<pre>
<b>BalloonInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Balloon will trigger the SoundPart  
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger the SoundPart when they match the color of the SoundPart. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>Cooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How long the SoundPart will remain inactive after being activated
</pre>

<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the SoundPart should be invisible when the Tower loads
</pre>

<pre>
<b>OneTimeUse</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the SoundPart should only work once
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger the SoundPart  
</pre>

<pre>
<b>PlayGlobal</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the Sound should be played globally
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger the SoundPart
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger the SoundPart
</pre>
