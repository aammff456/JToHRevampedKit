# ButtonDeactivator

▫️ <b>Type:</b> 🔲 BasePart  
▫️ <b>Description:</b> When touched, will attempt to unpress Buttons that are linked to it

## Structure
<pre>
▫️ 🔲 ButtonDeactivator <sup><b>Tag:</b> <i>ClientObject</i></sup>
</pre>

## When Disabled
<pre>
Touching the ButtonDeactivator will do nothing
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
▫️ <b>Description:</b> How long the ButtonDeactivator will remain inactive after being activated
</pre>

<pre>
<b>DeactivateAll</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, all Buttons will attempt to be unpressed
</pre>

<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> If enabled, the ButtonDeactivator will be invisible when it is loaded into the Tower. This is useful if you want to be able to see the ButtonDeactivator while editing, but not while playing
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger the ButtonDeactivator  
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger the ButtonDeactivator
</pre>

<pre>
<b>TargetGroup</b>  
<hr>
▫️ <b>Type:</b> string  
▫️ <b>Description:</b> If this field is given a value, it will only affect Buttons that have that same value as a tag. If this field is left blank, it will only affect Buttons that match the color of the ButtonDeactivator
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger activation of the Button  
</pre>
