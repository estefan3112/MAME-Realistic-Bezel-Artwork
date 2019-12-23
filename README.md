# MAME-Realistic-Bezel-Artwork

These Arcade Bezels provide the impression of (more or less heavily) used arcade machines, which I particularly like. This is a relaunch (WIP) for platform-independent MAME layout files (reset of GitHub history).

![alt text](screenshots/bankp.jpg "Bank Panic with Overlay in MAME")

# Parallel Retroarch Repository:

I plan to build up a parallel repository for Retroarch overlays here:
https://github.com/estefan3112/Retroarch-Realistic-Bezel-Artwork/blob/master/README.md

# You will find here:

1. Artwork for the official MAME distribution, which is an adaptation of John Merrit's artworks for RetroArch/Retropie:
https://forums.libretro.com/t/arcade-overlays/4084

2. Further artwork to arrive from Orionsangel as discussed here:
https://forums.libretro.com/t/my-realistic-arcade-bezels/10604
These .lay files aim to be platform independent and bare bone (with exceptions, where choice is nice).

3. Brand new 4k artwork from ArsInvictus:
https://forums.libretro.com/t/new-4k-bezel-overlays/25247
But he now produces his own .lay files for MAME, so please do not miss out on them, they are gorgeous!

4. I also included a template default.lay file, from which it is easy to build new layouts.

Explained for MAME on my Blog for MAME on modern Macs:
https://mameonmacs.blogspot.co.at/2017/02/porting-retropie-artwork-to-official.html

# Main contributions of this repository are:

(1) All bezels are based on 1080p (original contributions). Altough I scaled some of them up to 4000 x 2250 pixels, I will  revert back to 1080p because scaling up adds no value. If the screen resolution is bigger than 1080p, MAME automatically scales up.

(2) MAME Bezels are typically split into cabinet and screen, so that you can switch between Clear Screen and Scratch Screen inside the game. A showcase for MAME's great bezel design. If the screen is too blurry or too clear for you, note that all screens have an alpha value, which you can edit in the default.lay file. Thereby you can make the screen more or less transparent. Apparently, this does not apply to the Clear Screen setting, where there is no screen overlay at all.

(3) This repository aims to be platform independent. MAME .lay files should work all over, whereas Retroarch needs dedicated config files for every system. This will also explained in the parallel repository.

(4) I started to smoothen screen borders. All bezels including letter E are smoothened. If John Merrit's bezels require refinement, then these are the screen borders. See yourself. But this will take a while, it's a lot of work in Gimp, but very worth the effort!

A general note as regards Screen Size in these Layout files:
As explained to me by John in a post, nearly all traditional Cabinet monitors are 4:3 aspect ratio. Even if the game provides for a different internal screen resolution, they were displayed in 4:3. Although this results in distortion in some games, only this seems to provide the view of the original.

This is work in progress, more artwork to arrive. It takes very long because I am doing a lot of testing before I am satisfied with the results.

ALL WORK DONE HERE IS LICENSED UNDER GPL FOR FURTHER FREE USE.
