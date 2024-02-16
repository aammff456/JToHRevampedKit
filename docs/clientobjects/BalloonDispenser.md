# BalloonDispenser

A Part that can pop Balloons that touch it

## Structure
<pre>
▿ 🔲 BalloonDispenser <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▫️ ⚙️ InflateSound
    ▫️ ⚙️ PopSound
</pre>

## When Disabled
<pre>
Will not be able to spawn Balloons
</pre>

## Attributes
<pre>
<b>BalloonDensity</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines dense the Balloon part is, but does not determine the speed (The lower the value the more the attached object tends to influece horizontal movement)
</pre>

<pre>
<b>BalloonSize</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how big the Balloon is
</pre>

<pre>
<b>CanDismount</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines if the Player can dismount the Balloon by jumping
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger activation of the BalloonDispenser when they match the color of the Button. However, Parts that belong to the player are exempt from this rule 
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
▫️ <b>Description:</b> Determines whether a Player will trigger activation of the BalloonDispenser  
</pre>

<pre>
<b>PopTime</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how long the Balloon will last before popping
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger activation of the BalloonDispenser  
</pre>

<pre>
<b>RelativePopHeight</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how high the Balloon can travel relative to the BalloonDispenser before popping
</pre>

<pre>
<b>StringLength</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines the length of the Balloon string (the rope that connects the BalloonPart to the attached Part)
</pre>

<pre>
<b>Velocity</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how quickly the Balloon will travel upward
</pre>
