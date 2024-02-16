# Teleporter

A grouping of a teleport Part to a destination Part

## Structure
<pre>
▿ 📁 Teleporter
    ▫️ 🔲 DestinationPart
    ▫️ 🔲 TeleportPart
</pre>

## When Disabled
<pre>
Will not teleport anything that touches it
</pre>

## Attributes
<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only teleport when they match the color of the TeleportPart. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>Cooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How long the Teleporter will remain inactive after being activated
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger activation of the Teleporter  
</pre>

<pre>
<b>PlaySound</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the teleport sound it played on teleportation
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger activation of the Teleporter  
</pre>

<pre>
<b>RagdollPlayer</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the Player gets ragdolled after being teleported
</pre>

<pre>
<b>RetainOrientation</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether Parts/Player retain the same orientation relative to the World after teleporting
</pre>

<pre>
<b>TransitionEasingDirection</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingDirection  
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the Parts/Player to the new CFrame
</pre>

<pre>
<b>TransitionEasingStyle</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingStyle 
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the Parts/Player to the new CFrame
</pre>

<pre>
<b>TransitionSpeed</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines the speed for the Tween that transitions the Parts/Player to the new CFrame
</pre>

<pre>
<b>VelocityMultiplier</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Description:</b> The outgoing velocity is multiplied with this value. A value of 0 will stop anything from moving after teleporting. Values further from 0 will make outgoing Parts/Player move faster.
</pre>

## TeleportPart Attributes
<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the TeleportPart should be invisible when the Tower loads
</pre>

## DestinationPart Attributes
<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the DestinationPart should be invisible when the Tower loads
</pre>
