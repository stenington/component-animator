component-animator
================

A spritesheet animator brick for Mozilla Appmaker.

Spritesheets
------------

Spritesheets are defined by the following attributes:

* Required: 
    * *Spritesheet Source*: the source image
    * *Sprites Across*: horizontal width in sprites
    * *Sprites Down*: vertical height in sprites
* Optional:
    * *Top Bound*
    * *Bottom Bound*
    * *Left Bound*
    * *Right Bound*
    * *First Cell*
    * *Last Cell*

The required attributes let you divide the source image into a simple grid of evenly-sized sprites
to be displayed sequentially from left to right, row by row. 


The optional attributes let you further limit the portion of the source image used, and specify
different starting and ending frames for the animation.

<small>Test sprites made by dogchicken and are available at http://opengameart.org/content/cat-fighter-sprite-sheet.</small>