# Surf Map Thumbnails

Map thumbnails for surf maps for use in web apps that display map thumbnail images when querying game servers.

All map images are taken directly in-game and saved at 1920 x 1080.

An automated batch conversion process is used to automate the cropping of images to the correct sizes for various different web apps. This is done by cropping with the aspect ratio of the required image size.

This allows the correct sizing to occur avoiding the output being stretched or not in proportion.

## Usage

Simply upload the images within the web app folder that you'd like.

Currently supported web apps:

* SourceBans
* XI Server Management (Invision Power Board)

You can find more details on the image size and file path locations within each web app folder.

## Capturing your own map images

These instructions are written for Source based games, but you can likely adapt them for others.

* An application like [Fraps](http://www.fraps.com/) for taking in-game screenshots that save to disk directly on a hot key.
* Local listen/LAN dedicated server
* `sv_cheats 1`
* `cl_drawhud 0`
* Image manipulation software i.e. Photoshop

I would recommend you create a local listen or LAN dedicated server as you'll need to have `sv_cheats 1` set in order to disable HUD elements. Doing this on a public facing game server is massive security risk.

For the best image capturing, go into spectator mode and disable the HUD, get into the position you want and then take a screen capture. This provide a clean map image without any overlays.

## Generating your own thumbnails

All original map images are stored in the high resolution folder. This is where your image manipulation tool will need to look for images when in a batch process.

You will then need to generate recorded actions for each different image size you are generating where you crop to the correct size.

The versions provided were generated via the Actions functionality of Photoshop and then used in automation.

## Credits

All maps are copyright to their original creators. I take no credit in the ownership or development of any maps featured in any captures.