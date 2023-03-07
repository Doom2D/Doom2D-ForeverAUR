# PKGBUILDs for Doom 2D Forever game
This repo contains PKGBUILDs for Doom 2D Forever, what posted in AUR.

* doom2df-bin - binaries for game;
* doom2df-res - resources for game;
* doom2df-editor - map editor for game (**BROKEN WORK**)

## About editor
Actually, editor does not know how to search for files all over the file system or in special directories (/usr/share/doom2df or /home/<user>/.doom2df, etc), so it is possible to build the editor, but only by copying the binary and resources to "/home/<user>/.doom2df". Otherwise, the game will not see your custom maps. As soon as the problem is fixed, I will immediately post PKGBUILD on AUR.

**PLEASE, DON'T BUILD EDITOR FROM PKGBUILD!**
