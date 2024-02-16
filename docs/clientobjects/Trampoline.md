# Trampoline

A Part that bounces Objects that touch it

## Structure
<pre>
▿ 🔲 Trampoline <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▫️ ⚙️ BounceSound
</pre>

## When Disabled
<pre>
The Trampoline cannot be bounced on
</pre>

## Attributes
<pre>
<b>ColorStrict</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger the Trampoline when they match the color of the Trampoline. However, Parts that belong to the player are exempt from this rule 
</pre>

<pre>
<b>Cooldown</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> How long the Trampoline will remain inactive after being activated
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger the Trampoline  
</pre>

<pre>
<b>Power</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x > 0  
▫️ <b>Description:</b> How high things bounce on the Trampoline
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger the Trampoline
</pre>
