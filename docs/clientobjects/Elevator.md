# Elevator

A Part that applies a consistent linear force to Parts inside of it

## Structure
<pre>
▫️ 🔲 Elevator <sup><b>Tag:</b> <i>ClientObject</i></sup>
</pre>

## When Disabled
<pre>
The Elevator will not move Parts inside of it
</pre>

## Attributes
<pre>
<b>BalloonInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Balloon will be affected by the Elevator
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only be affected by the Elevator when their color matches the Elevator. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the Elevator should be invisible when the Tower loads
</pre>

<pre>
<b>MaxForce</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines the maximum amount of force the Elevator can apply to get Parts to the desired speed
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger activation of the DisappearingPart  
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will be affected by the Elevator
</pre>
