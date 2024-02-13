# Button

▫️ <b>Type:</b> 📚 Model  
▫️ <b>Description:</b> When activated, will toggle ButtonActivatedParts (or ButtonActivatedKillBricks) that are linked to it  
▫️ <b>Use of Tags:</b> Can describe a group for a ButtonDeactivator to target

## Structure
<pre>
▿ 📚 Button <sup><b>Tags:</b> <i>ClientObject, [ButtonDeactivator Groups]</i></sup>  
    ▫️ 🔲 Base  
    ▫️ 🔲 PressPart
    ▫️ ⚙️ ActivateSound
</pre>

## When Disabled
<pre>
Cannot be touched, and the Pressed attribute will not affect the Button when toggled
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
<b>HideTimer</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether the timer should be displayed or not
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger activation of the Button  
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger activation of the Button  
</pre>

<pre>
<b>TargetGroup</b>  
<hr>
▫️ <b>Type:</b> string  
▫️ <b>Description:</b> If this field is given a value, it will only affect ButtonActivatedParts that have that same value as a tag. If this field is left blank, it will only affect ButtonActivatedParts that match the color of the Button
</pre>

<pre>
<b>TimerDuration</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how long the timer lasts for the Button. When the timer finishes counting down, the Button will deactivate. If this value is set to 0, the Button will stay activated until an external force deactivates it
</pre>

<pre>
<b>TimerText</b>  
<hr>
▫️ <b>Type:</b> string  
▫️ <b>Description:</b> Determines what text the timer will display. If left blank, the timer will display the remaining time
</pre>

<pre>
<b>TimeStep</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how often the timer updates. Lower values tend to yield more accurate timers
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger activation of the Button  
</pre>

<pre>
<b>UseAnimation</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> If enabled, the Button will use an animation for its visual and can be unanchored or welded to other Parts. However, the colored Part of the Button will only ever move down 0.75 studs. If disabled, the Button will be forcefully anchored, but the distance the colored Part of the Button moves down depends on the depth of its base Part (ex: If the base is 5 studs high then the colored part will move down 4.75 studs when the Button is activated)
</pre>
