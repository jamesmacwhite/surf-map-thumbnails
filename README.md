# Surf Map Thumbnails

Additional map thumbnails for surf maps for use in SourceBans and other web apps that display map thumbnail images.

All map images are taken directly in-game and saved at 1920 x 1080 at 1080p.

A batch conversion process is automated to crop and resize images to the correct sizes for various web apps.

## Usage

Simply upload the image folder path relative to the web app that supports displaying map images.

The high resolution image folder is the original images at their native size when taken in-game.

Currently supported web apps and image paths:

* SourceBans - sourcebans/images/maps
* XI Server Management (Invision Power Board) - uploads/servermgnt/maps

## Creating your own map thumbnails

These instructions are written for Source based games. In order to create your own images you'll need the following:

* An application like [Fraps](http://www.fraps.com/) for taking in-game screenshots that save to disk directly on a hot key.
* Local listen/LAN dedicated srcds server
* `sv_cheats 1`
* `cl_drawhud 0`

I would recommend you create a local listen or LAN dedicated server as you'll need to run `sv_cheats 1` to disable HUD elements. Doing this on a public facing game server is massive security risk.

For the best image capturing, go into spectator mode and disable the HUD, get into the position you want and then take a screen capture. This provide a clean map image without any overlays.



