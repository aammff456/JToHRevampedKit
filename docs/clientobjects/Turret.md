# Turret

A part that periodically fires projectiles that can deal damage

## Structure
<pre>
▿ 📚 Turret <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▫️ 🔲 Base
    ▫️ 🔲 TurretProjectile
    ▫️ ⚙️ FireSound
</pre>

## When Disabled
<pre>
Will not teleport anything that touches it
</pre>

## Attributes
<pre>
<b>FireCooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How often the waits until shooting the next projectile
</pre>

<pre>
<b>PartsCollide</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not TurretProjectiles get destroyed when hitting a part
</pre>

<pre>
<b>PlayersCollide</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not TurretProjectiles get destroyed when hitting a player
</pre>

<pre>
<b>ProjectileDamage</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how much damage TurretProjectiles deal to the Player
</pre>

<pre>
<b>ProjectileLifetime</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how long TurretProjectiles last before they get destroyed
</pre>

<pre>
<b>ProjectilesCollide</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not TurretProjectiles get destroyed by other TurretProjectiles
</pre>

<pre>
<b>ProjectileVelocity</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how fast the TurretProjectiles move
</pre>
