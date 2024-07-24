# 2. Lights in Unreal Engine

<h2>OVERVIEW</h2>
<h3>Objective</h3>
<p>In this module, we're going to take a quick look at the basics of lights in Unreal Engine.</p>
<hr>
<h3>Part 1: Lights I</h3>
<p><iframe src="https://www.youtube.com/embed/aUQkjlq2GxI?rel=0" width="560" height="315" allowfullscreen="allowfullscreen" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe></p>
<h3>Part 2: Lights II</h3>
<p><iframe src="https://www.youtube.com/embed/k3c4nUYVZHI?rel=0" width="560" height="315" allowfullscreen="allowfullscreen" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe></p>
<h3>Part 3: Lighting with Time of Day</h3>
<p><iframe src="https://www.youtube.com/embed/g77mKqxv0b0?rel=0" width="560" height="315" allowfullscreen="allowfullscreen" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe></p>
<p>&nbsp;</p>
<hr>
<h2>Types of Lights</h2>
<h3>Point Lights</h3>
<p><img style="float: right; padding: 0 0 20px 20px;" src="https://vertexschool.instructure.com/courses/172/files/10609/preview?verifier=9JFJVeo1xnvTvrFH48wfLz4gx04tylc7y0OgjgfP" alt="LightTypes - Point.jpg" width="580" height="328" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/172/files/10609" data-api-returntype="File"></p>
<p><strong>Point Lights</strong><span>&nbsp;work much like a real world light bulb, emitting light in all directions from the light bulb's tungsten filament. However, for the sake of performance, Point Lights are simplified down emitting light equally in all directions from just a single point in space. Point lights are great for lights that are meant to extend lights in all directions. You can also adjust the length to simulate something like a tube light.</span></p>
<p>&nbsp;</p>
<p><em><strong>Properties of a Point Light:</strong></em></p>
<ul>
<li>Omni Directional</li>
<li>Radial Light</li>
<li>Good for tube lights, lightbulbs, or other central focus lights</li>
</ul>
<p>&nbsp;</p>
<p>&nbsp;</p>
<hr style="clear: both;">
<h3>Spot Lights</h3>
<p><img style="float: right; padding: 0 0 20px 20px;" src="https://vertexschool.instructure.com/courses/172/files/10612/preview?verifier=NejiDBoCO92ECI6ipJwg81Zc56VTZpPAlMGnIr69" alt="LightTypes - Spot.jpg" width="580" height="328" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/172/files/10612" data-api-returntype="File"></p>
<p><strong>Spot lights</strong> are concentrated or focused lights. Similar to point lights, they emit from a central point and fan out into a cone shape. These lights have settings that allow you to control the angle and spred of the projected light cone. The cone consists of an inner and outer cone with different spreads, which allows for a soft contrast or falloff between the two cones.</p>
<p>&nbsp;</p>
<p><em><strong>Properties of a Spot Light:</strong></em></p>
<ul>
<li>Single Directional</li>
<li>Cone shape</li>
<li>Good for overhead lights, actual spot lights, or inset lighting</li>
</ul>
<p>&nbsp;</p>
<hr style="clear: both;">
<h3>Directional Lights</h3>
<p><img style="float: right; padding: 0 0 20px 20px;" src="https://vertexschool.instructure.com/courses/172/files/10606/preview?verifier=wMJMhPloitOUmrDX8TldQwJRyclG9UFeQf20M9Y6" alt="LightTypes - Directional.jpg" width="580" height="328" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/172/files/10606" data-api-returntype="File"></p>
<p><strong>Directional lights</strong> are a type of light designed to project light from a source that is infinitely far away from your scene. Typically named "Light Source" when creating a New Default Level in Unreal, the Directional Light's primary use is to simulate sun light or moon light. This light source does not radiate from a central point within a scene due to it coming from so far away, so it is controlled by the angle or direction the light is being cast from.</p>
<p>When using a Directional light, you will only ever use one of these in your scene.</p>
<p>&nbsp;</p>
<p><em><strong>Properties of a Directional Light:</strong></em></p>
<ul>
<li>Single Directional</li>
<li>Based on a source too far away to show a central point</li>
<li>Good for sun light and moon light</li>
</ul>
<hr style="clear: both;">
<h3>Sky Lights</h3>
<p><img style="float: right; padding: 0 0 20px 20px;" src="https://vertexschool.instructure.com/courses/172/files/10611/preview?verifier=m0fyW37c3ZUUTxf7YsiZ4SeWqBGBNvf9H7v19qrf" alt="Skylight.jpg" width="580" height="657" data-api-endpoint="https://vertexschool.instructure.com/api/v1/courses/172/files/10611" data-api-returntype="File"></p>
<p><strong>Sky lights</strong> are a special case light that does not act like the other lights. These lights simulate an HDRI environment. By default, they take information from your sky and create a virtual HDRI lighting scenario for your scene. Alternatively when using the premade cubemap setting, you can plug in an actual HDRI map that the skylight will use. From there, you can also tint the overall color and control the intensity. The skylight provides ambient light that typically controls the color in your shadows.</p>
<p>When using a sky light, you will only ever use one in your scene.</p>
<p><em><strong>Properties of a Sky Light:</strong></em></p>
<ul>
<li>Special Case Light</li>
<li>Simulates HDRI&nbsp;Based on a skybox and it's color variations or a using a premade cubemap (HDRI texture)</li>
<li>Good for fill light from the sky</li>
<li>Controls the light in the shadows</li>
</ul>
<p>&nbsp;</p>