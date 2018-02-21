# Retroarch Bezel Artwork Explained

Retroarch config files are quite different to MAME. This will be much more work, but is probably worth the effort. In Retroarch, sophisticated overlays like these need more configuration than in MAME. However, Retroarch MAME bears other huge advantages, in particular shader sophistication and other finetuning.

Retroarch overlays come in two parts:

1. Overlay and image cfg file need to be in the Overlay directory defined in Retroarch. This is different from system to system:
- Retropie: /opt/retropie/emulators/retroarch/overlays/ -> here create a directory called arcade-bezel-overlays
- MacOS: :/Contents/Resources/overlays/ -> this is in the Retroarch App Bundle, again, create this directory arcade-bezel-overlays
- Windows: ...
- Linux: ...
The .cfg file configured here is then defined in the Game-specific config file. So if you change the above paths, you need to rewrite the path in the Game-specific config files as well.

2. The Game-specific config file provides for the necessary parameters, in particular Overlay orientation and screen size, so this file is dependent on your screen resolution. This makes it less partable than MAME .lay files.
The files in this repository are designed for 1080p of Retropie. For my iMac (Late 2013), for example, I have to scale the values up by 1.33, and they work. This will be your work.

Location of the Game-specific config files:
- Retropie: /opt/retropie/configs/all/retroarch/config/((directory of used Retroarch core))
- MacOS: /Users/((username))/Library/Application\ Support/RetroArch/config/((directory of used Retroarch Core))/
- Windows: ...
- Linux: ...

RECOMMENDED STEPS FOR USAGE:
1. Create a new directory called arcade-bezel-overlays in the default directory of your system indicated above.
2. Take the Overlay graphic files and put them into the directory of your choice. Subdirectories are not needed. 
3. Choose a Retroarch Core that you want to use with the Overlays, can be more than one.
4. Put the Game-specific config files into the respective sub-diretory of the Core.

The game should then immediately start with the Arcade Bezel. If nothing happens, recheck files (3 per game) and directories.
