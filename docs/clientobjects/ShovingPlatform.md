# ShovingPlatform

A Platform that will shove forward and then return to its starting position repeatedly

## Structure
<pre>
▿ 📚 ShovingPlatform <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▫️ ➡️ PrismaticConstraint
    ▿ 🔲 Base 
        ▫️ 🔹Attachment0
    ▿ 🔲 MainPart 
        ▫️ 🔹Attachment1
</pre>

## When Disabled
<pre>
The ShovingPlatform will freeze in the next stable state and will stop moving
</pre>

## Attributes
<pre>
<b>InDelay</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how long the Platform waits in the shoved position before attempting to return to its default state
</pre>

<pre>
<b>InSpeed</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how quickly the Platform moves to its default state
</pre>

<pre>
<b>OutDelay</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how long the Platform waits in the default position before attempting to move to its shoved state
</pre>

<pre>
<b>OutSpeed</b>  
<hr>
▫️ <b>Type:</b> number
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> Determines how quickly the Platform moves to its shoved state
</pre>
