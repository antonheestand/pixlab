# pixlab

Powered by [PixelKit](https://github.com/hexagons/pixelkit) and Metal

![](https://github.com/hexagons/pixlab/blob/master/Assets/Demos/pixlab_demo0.gif?raw=true)

## Install

Add [pixlab](https://github.com/hexagons/pixlab/raw/master/pixlab) to `/usr/local/bin/`

## Examples

~~~~
$ pixlab ~/Desktop/pix_out.png --metallib ~/PixelKitShaders-macOS.metallib --view
RenderKit ready to render.
a = /Users/<user>/Desktop/pix_in_a.png
b = /Users/<user>/Desktop/pix_in_b.png
a + b
a * b
a -> b
:q!
~~~~

~~~~
$ pixlab ~/Desktop/pix_out.png --metallib ~/PixelKitShaders-macOS.metallib --view
RenderKit ready to render.
ramp = gradient(1024)
ramp.
.scale
.offset
.bgColor
.color
.position
.direction
ramp.direction = .
.horizontal
.vertical
.radial
.angle
ramp.direction = .angle
ramp
~~~~

You can find the Metal library [here](https://github.com/hexagons/PixelKit/tree/master/Resources/Metal%20Libs)
