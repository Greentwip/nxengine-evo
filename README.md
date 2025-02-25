# UWP and Xbox One port
This project was forked from [NXEngine-evo](https://github.com/nxengine/nxengine-evo) and later
ported for the UWP by Victor Lopez. As intended, this GitHub fork will also host the Xbox One port.

# SDL
It was a challenge to obtain and compile the correct UWP SDL libs, it required some modification,
as those aren't really being updated so if your project needs SDL2 for UWP feel free to grab the
libs that were ported.

# NXEngine-evo
A somewhat upgraded/refactored version of [NXEngine](http://nxengine.sourceforge.net/) by Caitlin Shaw.

### [Support this project on Patreon!](https://www.patreon.com/sarcasticat)

[![Build Status](https://travis-ci.org/nxengine/nxengine-evo.svg?branch=master)](https://travis-ci.org/nxengine/nxengine-evo) [![Build status](https://ci.appveyor.com/api/projects/status/85orsvsorwbvct25?svg=true)](https://ci.appveyor.com/project/nxengine/nxengine-evo/branch/master)

![Screenshot](https://raw.githubusercontent.com/nxengine/nxengine-evo/master/screenshot.png)

## Running the game
 * Check the wiki for [Linux](https://github.com/nxengine/nxengine-evo/wiki/Building-on-Linux), [macOS](https://github.com/nxengine/nxengine-evo/wiki/Building-on-macOS), [Windows](https://github.com/nxengine/nxengine-evo/wiki/Building-on-Windows) and [UWP](https://github.com/Greentwip/nxengine-evo/wiki/Building-for-UWP) instructions if you'd like to build from source.
 * Check the [Releases](https://github.com/nxengine/nxengine-evo/releases) page and download the latest version if you'd rather not build it yourself.

## Differences from the original version of NXEngine:
* Port to SDL2 (thanks to [PIlin](https://github.com/PIlin/NXEngine-iOS))
* More resolutions and proper widescreen support up to Full HD (thanks to [EXL](https://github.com/EXL/NXEngine))
* Animated character portraits
* Modern main menu
* Credits graphics specific to the Mimiga Mask ending
* Localization support
* Force feedback support
* Custom soundtrack support
* Initial mod support
* Vita/Switch versions
* Cleaner and partly-refactored code
* Tons of gameplay-related bugfixes
* Removed built-in data extractor
* Removed replays, as they were buggy/not implemented anyway
