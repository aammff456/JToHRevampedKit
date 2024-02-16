# MusicPartModifier

A Part that will modify a MusicPart and/or its Music when touched

## Structure
<pre>
▫️ 🔲 MusicPartModifier <sup><b>Tag:</b> <i>ClientObject</i></sup>
</pre>

## When Disabled
<pre>
Will not modify MusicParts/Music
</pre>

## Attributes
<pre>
<b>BalloonInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Balloon will trigger the MusicPartModifier 
</pre>

<pre>
<b>ChangeMusicPriority</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the MusicPartModifier should modify the target MusicPart's MusicPriority attribute
</pre>

<pre>
<b>ChangePlaybackSpeed</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the MusicPartModifier should modify the target MusicPart's Music's PlaybackSpeed
</pre>

<pre>
<b>ChangeTimePosition</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the MusicPartModifier should modify the target MusicPart's Music's TimePosition
</pre>

<pre>
<b>ChangeVolume</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the MusicPartModifier should modify the target MusicPart's Music's Volume
</pre>

<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger the MusicPartModifier when they match the color of the MusicPartModifier. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>Cooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How long the MusicPartModifier will remain inactive after being activated
</pre>

<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the MusicPartModifier should be invisible when the Tower loads
</pre>

<pre>
<b>NewMusicPriority</b>  
<hr>
▫️ <b>Type:</b> number   
▫️ <b>Description:</b> Determines the new MusicPriority the target MusicPart will take
</pre>

<pre>
<b>NewPlaybackSpeed</b>  
<hr>
▫️ <b>Type:</b> number   
▫️ <b>Description:</b> Determines the new PlaybackSpeed the target MusicPart's Music will take
</pre>

<pre>
<b>NewTimePosition</b>  
<hr>
▫️ <b>Type:</b> number   
▫️ <b>Description:</b> Determines the new TimePosition the target MusicPart's Music will take
</pre>

<pre>
<b>NewVolume</b>  
<hr>
▫️ <b>Type:</b> number   
▫️ <b>Description:</b> Determines the new Volume the target MusicPart's Music will take
</pre>

<pre>
<b>OneTimeUse</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the MusicPartModifier should only work once
</pre>

<pre>
<b>PermanentEffects</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether or not the MusicPartModifier's effects should be permanent
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger the MusicPartModifier  
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger the MusicPartModifier  
</pre>

<pre>
<b>TargetClientObjectId</b>  
<hr>
▫️ <b>Type:</b> string  
▫️ <b>Description:</b> Affects the MusicPart with the specified Id
</pre>

<pre>
<b>TurretInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Turret projectile will trigger the MusicPartModifier  
</pre>
