# PushboxModifier

A Part that modified a touching Pushbox in some way

## Structure
<pre>
▫️ 🔲 PushboxModifier
</pre>

## When Disabled
<pre>
Will not modify touching Pushboxes
</pre>

## Attributes
<pre>
<b>ChangeColor</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the color of the touching Pushbox should be changed
</pre>

<pre>
<b>ChangeSize</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the size of the touching Pushbox should be changed
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Pushboxes can only trigger the PushboxModifier when they match the color of the PushboxModifier
</pre>

<pre>
<b>Cooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How long the PushboxModifier will remain inactive after being activated
</pre>

<pre>
<b>DestroyPushbox</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, touching Pushboxes will be destroyed

<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the PushboxModifier should be invisible when the Tower loads
</pre>

<pre>
<b>NewColor</b>  
<hr>
▫️ <b>Type:</b> Color3   
▫️ <b>Description:</b> Determines the new color of touching Pushboxes
</pre>

<pre>
<b>NewSize</b>  
<hr>
▫️ <b>Type:</b> Vector3   
▫️ <b>Description:</b> Determines the new size of touching Pushboxes
</pre>

<pre>
<b>TransitionEasingDirection</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingDirection  
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the touching Pushbox to its new state
</pre>

<pre>
<b>TransitionEasingStyle</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingStyle 
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the touching Pushbox to its new state
</pre>

<pre>
<b>TransitionTime</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines the speed for the Tween that transitions the touching Pushbox to its new state
</pre>
