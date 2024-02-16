# DisappearingPart

A Part that disappears when touched

## Structure
<pre>
▿ 🔲 DisappearingPart <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▫️ ⭕️ SelectionBox
</pre>

## When Disabled
<pre>
The Part will not disappear
</pre>

## Attributes
<pre>
<b>BalloonInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Balloon will trigger activation of the DisappearingPart  
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger activation of the DisappearingPart when they match the color of the DisappearingPart. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>FadeEasingDirection</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingDirection  
▫️ <b>Description:</b> Determines the easing direction for the Tween that fades the Part
</pre>

<pre>
<b>FadeEasingStyle</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingStyle 
▫️ <b>Description:</b> Determines the easing direction for the Tween that fades the Part
</pre>

<pre>
<b>FadeTime</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how fast the Part fades
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger activation of the DisappearingPart  
</pre>

<pre>
<b>FadeTime</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how fast the Part reappears after fully disappearing
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger activation of the DisappearingPart  
</pre>
