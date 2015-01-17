# Surf Map Thumbnails

Additional map thumbnails for surf maps for use in SourceBans and other web apps that display map thumbnail images.

All map images are taken directly in-game and saved at 1920 x 1080 at 1080p.

A batch conversion process is automated to crop and resize images to the correct sizes for various web apps.

## Usage

Simply upload the image folder path relative to the web app that supports displaying map images.

The high resolution image folder is the original images at their native size when taken in-game.

Currently supported web apps and image paths:

* SourceBans - sourcebans/images/maps
* XI Server Management (Invision Power Board) - uploads/servermgnt

## Creating your own map thumbnails

These instructions are written for Source based games. In order to create your own images you'll need to the following:

* An application like [Fraps](http://www.fraps.com/) for taking in-game screenshots and saving to disk directly.
* Local listen/LAN dedicated srcds server
* `sv_cheats 1`
* `cl_drawhud 0`

I would recommend you create a local listen or LAN dedicated server as you'll need to run `sv_cheats 1` to disable HUD elements. Doing this on a public facing game server is massive security risk.

For the best image capturing, you can go into spectator mode, position yourself for the map capture and then run `cl_drawhud 0` which provide a clean image capture.



