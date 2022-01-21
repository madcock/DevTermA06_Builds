# emulators
* [Dolphin 5.0-15906](https://github.com/dolphin-emu/dolphin) [^1] - GameCube / Wii emulator; details at the [official website](https://dolphin-emu.org/) 
```
  tar -xzf Dolphin5.0-15906.tgz
```
* [Flycast v1.2-217-g8ee9f1b1](https://github.com/flyinghead/flycast) [^1] - Sega Dreamcast, Naomi and Atomiswave emulator; details at the [official website](https://github.com/TheArcadeStriker/flycast-wiki/wiki) 
```
  tar -xzf flycast.1.2-217-g8ee9f1b1.tgz
```
* [MAME v0.239 (mame0239-192-g70295eff162)](https://github.com/mamedev/mame) [^2] - Multiple Arcade Machine Emulator; details at the [official website](https://github.com/TheArcadeStriker/flycast-wiki/wiki) 
```
  tar -xzf MAME.0239.tgz
```
* [PPSSPPSDL v1.12.3-722-gb1d158e3e](https://github.com/hrydgard/ppsspp) [^1] - PSP emulator; details at the [official website](https://www.mamedev.org/) 
```
  tar -xzf PPSSPPSDL.v1.12.3-722-gb1d158e3e.tgz
```
* [Stella 6.6](https://github.com/stella-emu/stella) - Atari 2600 emulator; details at the [official website](https://stella-emu.github.io/)
```
 sudo dpkg -i stella_6.6_arm64.deb
 sudo apt-get install -f
```
[^1]: You'll need to move the files into their proper locations! This is just an archive based on the install_manifest.txt produced during build/install.
[^2]: Built as "mamearcade" -- does NOT include MESS. Also does not include the additional tools. Packaged with MAME 0.239 distribution files from the Windows version.
