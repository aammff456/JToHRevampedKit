# TurretProjectileModifier

A Part that modified a touching TurretProjectile in some way

## Structure
<pre>
▫️ 🔲 TurretProjectileModifier <sup><b>Tag:</b> <i>ClientObject</i></sup>
</pre>

## When Disabled
<pre>
Will not modify touching TurretProjectiles
</pre>

## Attributes
<pre>
<b>ChangeColor</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the color of the touching TurretProjectile should be changed
</pre>

<pre>
<b>ChangeSize</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the size of the touching TurretProjectile should be changed
</pre>

<pre>
<b>ChangeSpeed</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the speed of the touching TurretProjectile should be changed
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, TurretProjectiles can only trigger the TurretProjectileModifier when they match the color of the TurretProjectileModifier
</pre>

<pre>
<b>Cooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How long the TurretProjectileModifier will remain inactive after being activated
</pre>

<pre>
<b>DestroyTurretProjectile</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, touching TurretProjectiles will be destroyed

<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the TurretProjectileModifier should be invisible when the Tower loads
</pre>

<pre>
<b>NewColor</b>  
<hr>
▫️ <b>Type:</b> Color3   
▫️ <b>Description:</b> Determines the new color of touching TurretProjectiles
</pre>

<pre>
<b>NewSize</b>  
<hr>
▫️ <b>Type:</b> Vector3   
▫️ <b>Description:</b> Determines the new size of touching TurretProjectiles
</pre>

<pre>
<b>NewSpeed</b>  
<hr>
▫️ <b>Type:</b> Vector3   
▫️ <b>Description:</b> Determines the new speed of touching TurretProjectiles
</pre>

<pre>
<b>TransitionEasingDirection</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingDirection  
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the touching TurretProjectile to its new state
</pre>

<pre>
<b>TransitionEasingStyle</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingStyle 
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the touching TurretProjectile to its new state
</pre>

<pre>
<b>TransitionTime</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines the speed for the Tween that transitions the touching TurretProjectile to its new state
</pre>
