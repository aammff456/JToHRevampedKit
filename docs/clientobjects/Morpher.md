# Morpher

▫️ <b>Type:</b> 📚 Model
▫️ <b>Description:</b> A set of Buttons and Parts that are able to morph a central Part to various states

## Structure
<pre>
▿ 📚 Morpher <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▿ 📚 MorpherButton
        ▫️ 🔲 Base
        ▫️ 🔲 MorphDestination
        ▫️ 🔲 PressPart
        ▫️ ⚙️ ActivateSound
    ▿ 📚 MorpherResetter
        ▫️ 🔲 Base
        ▫️ 🔲 PressPart
    ▫️ 🔲 MorphPart
    ▫️ ⚙️ MorpherResetSound
    ▫️ ⚙️ MorpherTickSound
</pre>

## When Button Disabled
<pre>
Touching the Button will do nothing and the Pressed attribute will not affect the Button when toggled
</pre>

## Morpher Attributes
<pre>
<b>TimerEndedUnmorphEasingDirection</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingDirection  
▫️ <b>Description:</b> Determines the easing direction for the Tween that returns the MorphPart to its default state after a MorpherButton Timer has ended
</pre>

<pre>
<b>TimerEndedUnmorphEasingStyle</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingStyle 
▫️ <b>Description:</b> Determines the easing style for the Tween that returns the MorphPart to its default state after a MorpherButton Timer has ended
</pre>

<pre>
<b>TimerEndedUnmorphSpeed</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines the speed for the Tween that returns the MorphPart to its default state after a MorpherButton Timer has ended
</pre>

## MorpherButton Attributes
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
<b>MorphEasingDirection</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingDirection  
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the MorphPart to its new state
</pre>

<pre>
<b>MorphEasingStyle</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingStyle 
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the MorphPart to its new state
</pre>

<pre>
<b>MorphSpeed</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines the speed for the Tween that transitions the MorphPart to its new state
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger activation of the Button  
</pre>

<pre>
<b>PlayTickSound</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the Button should play a tick sound when the morph lasts for a limited amount of time
</pre>

<pre>
<b>Pressed</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When toggled, will either cause the Button to press or unpress based on its current state
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger activation of the Button  
</pre>

<pre>
<b>TimerDuration</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how long the timer lasts for the Button. When the timer finishes counting down, the Button will deactivate. If this value is set to 0, the Button will stay activated until an external force deactivates it
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger activation of the Button  
</pre>

<pre>
<b>MorphSpeed</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines the speed for the Tween that transitions the MorphPart to its default state after the morph from the Button expires
</pre>

## MorpherResetter Attributes
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
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger activation of the Button  
</pre>

<pre>
<b>Pressed</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When toggled, will either cause the Button to press or unpress based on its current state
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger activation of the Button  
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger activation of the Button  
</pre>

<pre>
<b>UnmorphEasingDirection</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingDirection  
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the MorphPart to its default state
</pre>

<pre>
<b>UnmorphEasingStyle</b>  
<hr>
▫️ <b>Type:</b> Enum.EasingStyle 
▫️ <b>Description:</b> Determines the easing direction for the Tween that transitions the MorphPart to its default state
</pre>

<pre>
<b>UnmorphSpeed</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines the speed for the Tween that transitions the MorphPart to its default state
</pre>
