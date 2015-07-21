corona-sdk-glyphicons
=====================

A glyph icons module for corona sdk
Original icons from http://glyphicons.com/ by Jan Kovařík
Licensed under Creative Commons license

Test 2

usage:
```lua
local glyphicons = require("glyphicons")
local glyphicons_sprite = graphics.newImageSheet("glyphicons/glyphicons_sprites.png", glyphicons:getSheet())
-- display an info icon
local icon = display.newImage(glyphicons_sprite, glyphicons:getFrameIndex("circle_info")
```
Table of icons

![alt text](https://github.com/pjaol/corona-sdk-glyphicons/raw/master/glyphicons/all_icons.png "Glyphicons Table")
