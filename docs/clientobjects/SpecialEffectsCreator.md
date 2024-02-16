# SpecialEffectsCreator

A Part that will alter the effects of the game

## Structure
<pre>
▿ 🔲 SpecialEffectsCreator <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▫️ 🟪 EffectsConfiguration
</pre>

## When Disabled
<pre>
Will not alter the effects of the game
</pre>

## Attributes
<pre>
<b>BalloonInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Balloon will trigger the SpecialEffectsCreator  
</pre>

<pre>
<b>ChangeBloom</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the SpecialEffectsCreator should alter the Bloom
</pre>

<pre>
<b>ChangeBlur</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the SpecialEffectsCreator should alter the Blur
</pre>

<pre>
<b>ChangeColorCorrection</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the SpecialEffectsCreator should alter the ColorCorrection
</pre>

<pre>
<b>ChangeDepthOfField</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the SpecialEffectsCreator should alter the DepthOfField
</pre>

<pre>
<b>ChangeLighting/b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the SpecialEffectsCreator should alter the Lighting
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger the SpecialEffectsCreator when they match the color of the SpecialEffectsCreator. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>Cooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How long the SpecialEffectsCreator will remain inactive after being activated
</pre>

<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the SpecialEffectsCreator should be invisible when the Tower loads
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger the SpecialEffectsCreator  
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger the SpecialEffectsCreator
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger the SpecialEffectsCreator
</pre>
