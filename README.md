vintage-pil
===========

Uses the Python Imaging Library to give images a vintage look, with a variety of options.

Usage:

    import vintage, Image

    im = Image.load('some_picture.jpg')
    im = vintage.vintage_colors(im)
    im.save('vintage_picture.jpg')

Copyright (c) 2012 Nicholas White.  Licensed under the MIT license (see: LICENSE); if a copy of the license was not supplied along with the source code, one can be obtained via: http://www.opensource.org/licenses/mit-license.php
