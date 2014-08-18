component-animator
================

A spritesheet animator brick for Mozilla Appmaker.

Spritesheets
------------

Spritesheets are defined by the following attributes:

* Required: 
    * **Spritesheet Source**: the source image
    * **Sprites Across**: horizontal width in sprites
    * **Sprites Down**: vertical height in sprites
* Optional:
    * **Top Padding**: Pixel height of the area to ignore at the top of the source image
    * **Bottom Padding**: Pixel height of the area to ignore at the bottom of the source image
    * **Left Padding**: Pixel width of the area to ignore on the left side of the source image
    * **Right Padding**: Pixel width of the area to ignore on the right side of the source image
    * **First Cell**: Cell number at which to begin the animation (first cell is 0)
    * **Last Cell**: Cell number at which to end the animation

The required attributes let you divide the source image into a simple grid of evenly-sized sprites
to be displayed sequentially, beginning at the top left going from left to right, row by row.

The optional attributes let you further limit the portion of the source image used, and specify
different starting and ending frames within the spritesheet for the animation.

*Test sprites made by dogchicken and are available at http://opengameart.org/content/cat-fighter-sprite-sheet.*