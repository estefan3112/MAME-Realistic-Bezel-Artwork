# MAME-Retroarch-Realistic-Bezel-Artwork

Relaunch (WIP) in order to cover both MAME and Retroarch layout files (reset of GitHub history). You will find here:

1. Artwork for the official MAME distribution, which is an adaptation of John Merrit's artworks for RetroArch/Retropie:
https://forums.libretro.com/t/arcade-overlays/4084
Further artwork to arrive from Orionsangel as discussed here:
https://forums.libretro.com/t/my-realistic-arcade-bezels/10604
These .lay files aim to be platform independent and bare bone (with exceptions, where choice is nice).

2. Retroarch config files for the same overlays. This will be much more work, but is probably worth the effort. In Retroarch, sophisticated overlays like these need more configuration than in MAME. However, Retroarch MAME bears other huge advantages, in particular shader galore and other finetuning.

Explained on my Blog for MAME on modern Macs (WIKI to follow here):
https://mameonmacs.blogspot.co.at/2017/02/porting-retropie-artwork-to-official.html

Main contributions of this repository are:

(1) Scaled up to 4000 x 2250 pixels. (Note: I will probably revert to 1080p because scaling up adds no value, only adds file size)

(2) MAME Bezels are split into cabinet and screen. Inside of each game, you can choose between a Clear Screen and a Scratch Screen. This makes it possible to reduce the opacity of the scratches without limiting the overall beauty of the cabinet. Technically, the Alpha Channel of the Screen Artwork determines the intensity of the scratches and reflections on the screen.

(3) The MAME NEOGEO Artwork is a specialty: It is attached to every Neogeo Game on top of its own screens. This is damn cool, because you can always revert to a cool generic NEOGEO Cabinet with every single NEOGEO game. Also here, I added two cabinets, one with a Scrach Screen and one with a Clear Screen.

A note as regards Screen Size in these Layout files:
As explained to me by John in a post, all traditional Cabinet monitors are 4:3 aspect ratio. Even if the game provides for a different internal screen resolution, they were displayed in 4:3. Although this results in distortion in some games, only this seems to provide the view of the original.

For ease of use, I provide the files in directories, they can be easily zipped for the designated MAME Artwork directory in order to avoid subdirectories.

This is work in progress, more artwork to arrive.

ALL WORK DONE HERE IS LICENSED UNDER GPL FOR FURTHER FREE USE. 
