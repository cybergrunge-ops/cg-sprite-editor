# cg-sprite-editor
unhappy with sprite editors out there and also wanted to make my own to get better at javascript.

10-color sprites are stored as a string of digits between 0 and 9, comma, then a digit for the palette id to use

has 4 palettes by default, more can be added easily.


## future stuff to add
- palette editor
- more preset/demo sprites and palettes
- allow for adding custom properties to the sprite, that can later be used in a game engine
- flags for various things like collision, size, animation, etc

## development timeline
- initial upload
- allow drawing lines instead of having to click one individual pixel at a time
- added comma seperation to store palette id in sprite
- added more palettes, palette selector and more demo sprites
- added `tiled` display mode, made `drawSprite` function work
