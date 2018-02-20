# MAME Bezel Artwork Explained

This subsection contains:

1. Artwork for the official MAME distribution, which is an adaptation of John Merrit's artworks for RetroArch/Retropie:
https://forums.libretro.com/t/arcade-overlays/4084

Further artwork to arrive from Orionsangel as discussed here:
https://forums.libretro.com/t/my-realistic-arcade-bezels/10604

These .lay files aim to be platform independent and bare bone (with exceptions, where choice is nice). Should they not work in any system environment, I would be grateful for feedback.

MAME .lay files have some unique possibilities, which make them a very good choice for Bezel Artwork:

(1) They scale automatically to your display resolution. No adaptation is required as is the case with Retroarch Overlays. This makes them very portable.

(2) MAME Bezels are split into cabinet and screen. Inside of each game, you can choose between a Clear Screen and a Scratch Screen. This makes it possible to reduce the opacity of the scratches without limiting the overall beauty of the cabinet. Technically, the Alpha Channel of the Screen Artwork determines the intensity of the scratches and reflections on the screen.

(3) The MAME NEOGEO Artwork is a specialty: It is attached to every Neogeo Game on top of its own screens. This is damn cool, because you can always revert to a cool generic NEOGEO Cabinet with every single NEOGEO game. Also here, I added two cabinets, one with a Scrach Screen and one with a Clear Screen.

A note as regards Screen Size in these Layout files:
As explained to me by John in a post, all traditional Cabinet monitors are 4:3 aspect ratio. Even if the game provides for a different internal screen resolution, they were displayed in 4:3. Although this results in distortion in some games, only this seems to provide the view of the original.

HOW To USE:

1. For ease of use, I provide the files in directories, they can be easily zipped for the designated MAME Artwork directory in order to avoid subdirectories. 

2. Even without zipping them, you can test them immediately by putting them into the MAME Artwork folder under the respective game name.

WIP, more to come.