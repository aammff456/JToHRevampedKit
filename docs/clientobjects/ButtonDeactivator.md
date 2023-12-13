# ButtonDeactivator

▫️ <b>Type:</b> 🔲 BasePart  
▫️ <b>Description:</b> When touched, will disable Buttons that are linked to it

## Structure
<pre>
▫️ 🔲 ButtonDeactivator <sup><b>Tag:</b> <i>ClientObject</i></sup>
</pre>

## Attributes
<pre>
<b>Enabled</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> If disabled, the ButtonDeactivator will not affect any Buttons
</pre>

<pre>
<b>InvisibleOnLoad</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> If enabled, the ButtonDeactivator will be invisible when it is loaded into the Tower. This is useful if you want to be able to see the ButtonDeactivator while editing, but not while playing
</pre>

<pre>
<b>OnlyMatchingColorInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> When enabled, Parts can only trigger the ButtonDeactivator when they match the color of the ButtonDeactivator. However, Parts that belong to the player are exempt from this rule
</pre>

<pre>
<b>PlayerInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Player will trigger the ButtonDeactivator  
</pre>

<pre>
<b>PushboxInteraction</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> Determines whether a Pushbox will trigger the ButtonDeactivator
</pre>

<pre>
<b>TargetGroup</b>  
<hr>
▫️ <b>Type:</b> string  
▫️ <b>Description:</b> If this field is given a value, it will only affect Buttons that have that same value as a tag. If this field is left blank, it will only affect Buttons that match the color of the ButtonDeactivator
</pre>