# Image2Bytes
Convert .jpg files into a D ubyte array

This is a quick and dirty hack and an excuse for me to experiment with F#.

I needed an easy way to draw an image to a linear framebuffer for some
work on Fortress OS, and this fit the bill!

To use, you'll need to manually change the path to the .jpg in the source,
and you'll probably want a different variable name in the output as well.

With very little effort this could be modified to output C headers as well.
