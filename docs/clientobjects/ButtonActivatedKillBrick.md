# ButtonActivatedKillBrick

A KillBrick that is toggled on and off by a Button. When enabled, it is opaque, can be collided with, and can deal damage. When disabled, it is transparent or invisible, cannot be collided with, and might not deal damage

▫️ <b>Use of Tags:</b> Can describe a group for a Button to target

## Structure
<pre>
▿ 🔲 ButtonActivatedKillBrick
    ▫️ ✨ ParticleEmitter
</pre>

## Attributes
<pre>
<b>Damage</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how much damage the ButtonActivatedKillBrick should deal to the Player
</pre>

<pre>
<b>DamageWhenDisabled</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether the ButtonActivatedKillBrick should deal damage when toggled off
</pre>

<pre>
<b>FullHide</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether the ButtonActivatedKillBrick should be invisible when disabled
</pre>

<pre>
<b>Inverted</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines if a ButtonActivatedKillBrick should be enabled when disabled, and visa versa
</pre>
