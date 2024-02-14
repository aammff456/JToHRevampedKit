# DistanceAnchoredObject

A Part or Model that unanchors when the Player gets close enough

## Structure
<pre>
▫️ 🔲 DistanceAnchoredPart <sup><b>Tag:</b> <i>ClientObject</i></sup>
</pre>
<i>or</i>
<pre>
▿ 📚 DistanceAnchoredModel <sup><b>Tag:</b> <i>ClientObject</i></sup>
    ▫️ 🔲 Part
    ▫️ 🔲 ...
</pre>

## DistanceAnchoredPart Attributes
<pre>
<b>UnanchorDistance</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how close a Player has to be in order to cause the Part to unanchor
</pre>

## DistanceAnchoredModel Attributes
<pre>
<b>OnlyUnanchorPrimaryPart</b>  
<hr>
▫️ <b>Type:</b> boolean  
▫️ <b>Description:</b> If true, only the PrimaryPart of the Model needs to be unanchored. If false, all Parts in the Model will be unanchored
</pre>

<pre>
<b>UnanchorDistance</b>  
<hr>
▫️ <b>Type:</b> number  
▫️ <b>Constraints:</b> x >= 0  
▫️ <b>Description:</b> Determines how close a Player has to be in order to cause the Part(s) to unanchor
</pre>
