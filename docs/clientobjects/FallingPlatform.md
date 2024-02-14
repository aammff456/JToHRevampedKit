# FallingPlatform

A Platform that can fall when touched, where it can 

## Structure
<pre>
▿ 📚 FallingPlatform <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▫️ ➡️ PrimaticConstraint
    ▿ 🔲 Base 
        ▫️ 🔹Attachment0
    ▿ 🔲 Platform 
        ▫️ 🔹Attachment1
</pre>

## When Disabled
<pre>
Touching the FallingPlatform will do nothing
</pre>

## Attributes
<pre>
<b>BalloonInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Balloon will trigger activation of the FallingPlatform  
</pre>

<pre>
<b>CanCollideFalseAtMaxDepth</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether the Platform should become CanCollide false and transparent after it falls to its max depth
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger activation of the FallingPlatform when they match the color of the FallingPlatform. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>FallSpeed</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how fast the Platform falls
</pre>

<pre>
<b>MovementTimeout</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how long the Platform will wait in order to try and get itself unstuck
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger activation of the FallingPlatform  
</pre>

<pre>
<b>PlayerLegsStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not only the Legs of a Player can activate the FallingPlatform when PlayerInteraction is true
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger activation of the FallingPlatform  
</pre>

<pre>
<b>FallSpeed</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how fast the FallingPlatform returns to its resting position
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger activation of the FallingPlatform  
</pre>
