* SpriteFX.library will allocate Chip RAM buffers and link to them in a "SpritePort" structure that will be like a cross between a SimpleSprite and narrow ViewPort with linked regions so that sprites may be stacked side-by-side for greater width.

* Support will be there for 2 and 4 bitplane sprites.

* The command rows needed for the sprite support will be added during display and removed during blitting in order to allow super-bitmap vertical scrolling of taller than screen-size images.

* Interlace support via the Copper lists and separate buffers for odd and even pixels.
