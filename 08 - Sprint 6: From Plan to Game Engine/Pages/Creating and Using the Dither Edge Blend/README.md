# Creating and Using the Dither Edge Blend

<h2>Creating and Using the Dither Edge Blend</h2>
<p>Using the Dither Temporal AA functionality in Unreal can be a simple and easy way to make your objects blend in with things like terrain a lot easier. The steps are easy:</p>
<ol>
<li>Create a Material Function</li>
<li>Summon the DitherTemporalAA node and multiply it my a scalar parameter<br><img src="https://vertexschool.instructure.com/courses/172/files/10654/preview?verifier=b3102fXcZR21j16I1FVuTQHJr9hkwnE0QXfubRwS" alt="MF_Dither_Make.jpg" width="700" height="639" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/172/files/10654" data-api-returntype="File"><br><br></li>
<li>Feed the Material Function into the Pixel Depth Offset input of your Material Attributes<br><img src="https://vertexschool.instructure.com/courses/172/files/10607/preview?verifier=OwIVem3gwzLNJzR8HuLVvSUa2N45ACgrofFEEP72" alt="MF_Dither_Use.jpg" width="700" height="617" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/172/files/10607" data-api-returntype="File"><br><br></li>
<li>The DitherAmount parameter will now show up in your material instance to edit.
<ol>
<li>0 = Off, no edge blending</li>
<li>1 = Standard, like feeding the DitherTemporalAA node directly in</li>
<li>5 = Extreme value, try not to go over this value or you might content with some artifacts</li>
<li>1.5 - The ideal value in most situation</li>
</ol>
</li>
</ol>
<p>&nbsp;</p>