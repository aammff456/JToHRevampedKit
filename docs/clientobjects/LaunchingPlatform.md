# LaunchingPlatform

A Platform that falls and then returns back up very quickly, launching things

## Structure
<pre>
▿ 📚 LaunchingPlatform
    ▫️ ➡️ PrimaticConstraint
    ▿ 🔲 Base 
        ▫️ 🔹Attachment0
    ▿ 🔲 MainPart 
        ▫️ 🔹Attachment1
    ▿ 🔲 SecondaryPart 
        ▫️ ⏺ Weld Constraint
</pre>

## When Disabled
<pre>
Touching the LaunchingPlatform will do nothing
</pre>

## Attributes
<pre>
<b>BalloonInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Balloon will trigger activation of the LaunchingPlatform  
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger activation of the LaunchingPlatform when they match the color of the FallingPlatform. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>FallSpeed</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how fast the LaunchingPlatform falls
</pre>

<pre>
<b>LaunchResponsiveness</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Higher values means it takes the LanchingPlatform more time to reach its LaunchSpeed
</pre>

<pre>
<b>LaunchSpeed</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> The target speed of how fast the LanchingPlatform will move back toward its resting position
</pre>

<pre>
<b>MovementTimeout</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how long the LaunchingPlatform will wait in order to try and get itself unstuck
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
▫️ <b>Description:</b> Determines whether or not only the Legs of a Player can activate the LaunchingPlatform when PlayerInteraction is true
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger activation of the LaunchingPlatform  
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger activation of the LaunchingPlatform  
</pre>
