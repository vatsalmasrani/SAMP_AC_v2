SAMP_AC_v2
==========
[![Linux Build Status](https://travis-ci.com/Whitetigerswt/SAMP_AC_v2.svg?token=ENM294yxGXvxxZbK9fRC&branch=master)](https://travis-ci.com/Whitetigerswt/SAMP_AC_v2)
Version 2.0 of SAMP Anti-Cheat. This is a full re-code from the ground up.

Use
========== 
This program was used by thousands of players for [SA-MP (San Andreas Multiplayer)](http://www.sa-mp.com). It was usually used in conjunction with [attdef](https://github.com/Whitetigerswt/attdef). This program protected against various common cheats that were highly popular between the years 2014-2017. I would not recommend using this today for anti-cheat purposes as it is fairly dated. I believe it could be updated.

Features
==========
- Game File verification
- Process list verification (checks for illegal processes)
- Injected libraries verification (Checks for illegally injected DLL's)
- Extension to SA-MP. Provides many new functions to the SA-MP game client. Player's familiar with SA-MP+ should recognize some similar functionality.
- Hooks into main SA-MP network code to allow a seamless installation for server and client.
- DirectX and many game hooks to prevent advanced cheats.
- Verifies integrity of packets in the SA-MP network layer.
- Rudimentary thread analysis: Threads created by all modules were kept track of and monitored.
- Integration of the [Dynamic Natives](https://github.com/Whitetigerswt/Dynamic_Natives) proof-of-concept.
- Easy-to-install client that automatically detects GTA:SA and SA-MP installation.
- Easy-to-install server with vast documentation on new functions and callbacks.
- Many example Filterscripts showing functionality, easy to extend and implement in current gamemodes.
- Debugging counter-measures and advanced protection against software decompilation via the [Enigma Protector](https://www.enigmaprotector.com/en/about.html).
- Advanced configuration to prevent sync bugs, control c-bug speed, switch reload, vehicle blips
- Much much more...

Compiling
==========

Windows
----------
```
1) Download Visual Studio 2015 Community Edition - https://www.visualstudio.com/en-us/visual-studio-homepage-vs.aspx
2) Download Visual Studio 2013 SDK - https://www.microsoft.com/en-us/download/details.aspx?id=40758
3) Open acv2.sln with Visual Studio 2015
4) Switch to release mode
5) Compile
```

Client Specific
----------
* Ask Whitetiger to run the Enigma protector on the compiled file - you can use the demo for testing.
* Download nullsoft scriptable install system - http://nsis.sourceforge.net/Download
* Run sampac.nsi

Linux
----------
```
1) Use _32_-bit Ubuntu 14.04.3 LTS Through VMWare (Or whatever distro you want, Ubuntu is the easiest)
2) sudo apt-get update
3) sudo apt-get upgrade 
4) sudo apt-get install build-essential git g++-4.4 (Old version of g++ to allow compatability with older Linux distros)
5) Follow steps here to generate an ssh key and add to github: https://help.github.com/articles/generating-ssh-keys/
6) git clone git@github.com:Whitetigerswt/SAMP_AC_v2.git
7) cd to "ACv2_Server"
8) "make"
9) sampac.so should be located in ACv2_Server/bin/
```

Release builds
==========
Fully compiled release builds are available [here](https://whitetigerswt.github.io/SAMP_AC_v2/)

Gameplay
==========
- [vR in ACv2](https://www.youtube.com/watch?v=s4iZh54WLR4)
- [ROU vs UK - World Cup 10](https://www.youtube.com/watch?v=f9ZTRq6rtTU)
- [some tcws](https://www.youtube.com/watch?v=Bso6Fe4ymPs)
- [tcws](https://www.youtube.com/watch?v=H4mXAnNt2FQ)
- [57 vs sMb](https://www.youtube.com/watch?v=nndvDC-y2i0)


Questions, comments, suggestions, future development?
===========
[Ask me on the Discord](https://discord.gg/3NS5dMB)
