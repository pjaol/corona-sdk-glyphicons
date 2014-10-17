corona-sdk-glyphicons
=====================

A glyph icons module for corona sdk
Original icons from http://glyphicons.com/ by Jan Kovařík
Licensed under Creative Commons license


usage:
```lua
local glyphicons = require("glyphicons")
local glyphicons_sprite = graphics.newImageSheet("glyphicons/glyphicons_sprites.png", glyphicons:getSheet())
-- display an info icon
local icon = display.newImage(glyphicons_sprite, glyphicons:getFrameIndex("circle_info")
```

