# MovingPlatform

A set of Parts where a Platform moves between

## Structure
<pre>
▿ 📚 MovingPlatform
    ▫️ 🔲 2 
    ▫️ 🔲 ... 
    ▫️ 🔲 Platform 
</pre>

## When Disabled
<pre>
The Platform will freeze in the next stable state and will stop moving
</pre>

## Attributes
<pre>
<b>ObjectsStick</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not objects on top of the Platform stay on the Platform when it moves
</pre>

<pre>
<b>PositionsInvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the Platform positions are invisible when the Tower loads
</pre>

<pre>
<b>WaitTime</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how long it takes for the Platform to head toward the next location
</pre>

<pre>
<b>Responsiveness</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 5, x <= 200
▫️ <b>Description:</b> Determines how quickly the Platform moves to its next location
</pre>
