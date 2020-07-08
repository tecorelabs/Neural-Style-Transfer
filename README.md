# Neural-Style-Transfer

This is a torch implementation of the paper [A Neural Algorithm of Artistic Style](http://arxiv.org/abs/1508.06576)
by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge.

The paper presents an algorithm for combining the content of one image with the style of another image using
convolutional neural networks. Here's an example that maps the artistic style of
[The Starry Night](https://en.wikipedia.org/wiki/The_Starry_Night)
onto a night-time photograph of the Stanford campus:

<div align="center">
 <img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/starry_night_google.jpg" height="223px">
 <img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/hoovertowernight.jpg" height="223px">
 <img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/starry_stanford_bigger.png" width="710px">
</div>

Applying the style of different images to the same content image gives interesting results.
Here we reproduce Figure 2 from the paper, which renders a photograph of the Tubingen in Germany in a
variety of styles:

<div align="center">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/tubingen.jpg" height="250px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/tubingen_shipwreck.png" height="250px">

<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/tubingen_starry.png" height="250px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/tubingen_scream.png" height="250px">

<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/tubingen_seated_nude.png" height="250px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/tubingen_composition_vii.png" height="250px">
</div>

Here are the results of applying the style of various pieces of artwork to this photograph of the
golden gate bridge:


<div align="center"
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/golden_gate.jpg" height="200px">

<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/frida_kahlo.jpg" height="160px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/golden_gate_kahlo.png" height="160px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/escher_sphere.jpg" height="160px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/golden_gate_escher.png" height="160px">
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/woman-with-hat-matisse.jpg" height="160px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/golden_gate_matisse.png" height="160px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/the_scream.jpg" height="160px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/golden_gate_scream.png" height="160px">
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/starry_night_crop.png" height="160px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/golden_gate_starry.png" height="160px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/inputs/seated-nude.jpg" height="160px">
<img src="https://raw.githubusercontent.com/jcjohnson/neural-style/master/examples/outputs/golden_gate_seated.png" height="160px">
</div>
