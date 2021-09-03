# Yamagi Quake II

Yamagi Quake II is an enhanced client for id Software's Quake
II with focus on offline and coop gameplay. Both the gameplay and the graphics
are unchanged, but many bugs in the last official release were fixed and some
nice to have features like widescreen support and a modern OpenGL 3.2 renderer
were added. Unlike most other Quake II source ports Yamagi Quake II is fully 64-bit
clean. It works perfectly on modern processors and operating systems. Yamagi
Quake II runs on nearly all common platforms; including FreeBSD, Linux, NetBSD,
OpenBSD, Windows and macOS (experimental).

This code is built upon Icculus Quake II, which itself is based on Quake II
3.21. Yamagi Quake II is released under the terms of the GPL version 2. See the
LICENSE file for further information.

Original Yamagi Quake : https://github.com/yquake2/yquake2

## Documentation

Before asking any question, read through the documentation! The current
version can be found here: [doc/010_index.md](doc/010_index.md)

## Releases

The official releases (including Windows binaries) can be found at our
homepage: https://www.yamagi.org/quake2  
**Unsupported** preview builds for Windows can be found at
https://deponie.yamagi.org/quake2/misc/




## ( Modified for personal and private use. Unofficlal Build )

Added Switches
# -nocinema 
Deactivates the playing of the videos for mods or maps. According to which you do not need videos despite the fact that they are in the main directory of Quake 2 but are important for the Q2 main game. 

# -addondir
AddonDir can be used in combination with datadir. For example, I have the Quake2 main directory in
(1) "B:\Directory\Directory\[ Quake 2 Base ]\"
The mod or map is under
(2) "B:\Directory\Directory\[ Quake 2 Mod ]\Modname\Game Directory\"
-datadir points to (1)
-addondir points to (2) + set game "game directory"
I'm still using kmQuake2 and both ports point to same base directory. Stay organized and save space.

Compile: MingW
