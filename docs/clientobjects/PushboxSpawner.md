# PushboxSpawner

A grouping of a Button and a Pushbox, where the Button can spawn/respawn that Pushbox

## Structure
<pre>
▿ 📚 PushboxSpawner
    ▿ 📚 Button
        ▫️ 🔲 Base
        ▫️ 🔲 PressPart
    ▫️ 🔲 Pushbox
</pre>

## When Disabled
<pre>
Will not spawn/respawn the Pushbox
</pre>

## Attributes
<pre>
<b>BalloonInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Balloon will trigger activation of the Button  
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger activation of the Button when they match the color of the Button. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>Cooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How long the PushboxSpawner will remain inactive after being activated
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger activation of the Button  
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger activation of the Button  
</pre>

<pre>
<b>SpawnOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the Pushbox should spawn in automatically when the Tower loads
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger activation of the Button  
</pre>
