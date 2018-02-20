# MAME-Realistic-Bezel-Artwork
Artwork for the official MAME distribution, which is an adaptation of John Merrit's artworks for RetroArch/Retropie:
https://forums.libretro.com/t/arcade-overlays/4084

Further artwork to arrive from Orionsangel as discussed here:
https://forums.libretro.com/t/my-realistic-arcade-bezels/10604
These are MAME layouts, however for the Windows world with specific ini files. Here converted to pure .lay format.

Mostly merged into the official MAME Artwork available here (if available, I merge it into the Widescreen version):
http://www.progettosnaps.net/artworks/
If possible merged into Widescreen artwork available there.

Explained on my Blog for MAME on modern Macs (WIKI to follow here):
https://mameonmacs.blogspot.co.at/2017/02/porting-retropie-artwork-to-official.html

Main contributions of this repository are:

(1) Scaled up to 4000 x 2250 pixels. (Note: I will probably revert to 1920p because scaling up adds no value, but adds file size and also quite some complexity during conversion into a Rechtoarch/Retropie Overlay)

(2) Bezels are split into cabinet and screen. Inside of each game, you can choose between a Clear Screen and a Scratch Screen. This makes it possible to reduce the opacity of the scratches without limiting the overall beauty of the cabinet. Technically, the Alpha Channel of the Screen Artwork determines the intensity of the scratches and reflections on the screen.

(3) The NEOGEO Artwork is a specialty: It is attached to every Neogeo Game on top of its own screens. This is damn cool, because you can always revert to a cool generic NEOGEO Cabinet with every single NEOGEO game. Also here, I added two cabinets, one with a Scrach Screen and one with a Clear Screen.

A note as regards Screen Size in these Layout files:
As explained to me by John in a post, all traditional Cabinet monitors are 4:3 aspect ratio. Even if the game provides for a different internal screen resolution, they were displayed in 4:3. Although this results in distortion in some games, only this seems to provide the view of the original.

For ease of use, I provide the files in directories, they can be easily zipped for the designated MAME Artwork directory in order to avoid subdirectories.

This is work in progress, more artwork to arrive.

ALL WORK DONE HERE IS LICENSED UNDER GPL FOR FURTHER FREE USE. 
