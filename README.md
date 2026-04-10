# Table

| Project name                        | State  | Language     | Sloppiness      |
|-------------------------------------|--------|--------------|-----------------|
| 4jcraft                             | active | Meson/C++    | no-ai policy    |
| MinecraftConsoles                   | active | CMake/C++    | no-ai policy    |
| LCEMP                               | stale  | C++          | ?               |
| LegacyEvolved                       | active | Cmake/C++    | no-ai policy    |
| OpenLCE                             | ?      | CMake/C++    | ?               |
| Cactus-ModLoader                    | stale  | Meson/C++    | no-ai policy    |
| Axo ModLoader                       | active | Python, C++  | ai was used     |
| Faucet                              | stale  | CMake/C++    | written with ai |
| Java-to-MLCE-Texture-Pack-Converter | stale  | Python       | written by ai   |
| LCE-Qt-Launcher                     | active | Python, QT   | ?               |
| Legacy Console Launcher             | stale  | C#, WinForms | ?               |
| Emerald Legacy Launcher             | active | TS, Rust     | ?               |
| Flint                               | stale  | Zig          | looks generated |


# Minecraft LCE _forks_

## [4jcraft](https://github.com/4jcraft/4jcraft)
[![](./.github-assets/4jcraft.png)](https://github.com/4jcraft/4jcraft)

Scope of this project is to clean up, modernize, restructure and fix Minecraft LCE code

Restructuring is being done for maintainability and portability - this project aims to support a lot of platforms, including:
- Linux(main platform)
- Emscripten
- Android
- MacOSX

## [Yuricraft](https://github.com/Acemany/4jcraft)
Yuri-focused fork of 4jcraft. While 4jcraft is already woke, it does not have yuri in it, therefore the fork

Basically a reskin of 4jcraft, everything besides visuals is the same

## [MinecraftConsoles](https://github.com/MCLCE/MinecraftConsoles)
This project aims to Polish windows support, fix bugs and implement some features(such as multiplayer)

It does not do any crazy refactors and supports Windows only

## [LCEMP](https://github.com/LCEMP/LCEMP)
This is LCE with minor fixes and multiplayer

That repo does not contain the full source code and it does not contain assets

## [neoLegacy](https://github.com/LCE-Hub/neoLegacy) (formerly LegacyEvolved)
LegacyEvolved merged with LMRP(Legacy Minigames Revival Project)! Now it is called neoLegacy

This project aims to backport the newer title updates back to the leaked Legacy Console Edition (which is based on TU19)

## [OpenLCE](https://openlce.org/)
This fork aims at supporting mods and all platforms from leak and even more

Git repo is not accessible?


# Modloaders, injectors, patchers, and whatever they are

## [Cactus-ModLoader](https://github.com/MathiewMay/Cactus.ModLoader)
A fork-agnostic and cross-platform Mod Loader for LCE

Mods are written in LUA

Goals:
- [x] Add custom block and item registration with custom textures
- [x] Event system
- [x] Client and server modding using LUA scripting
- [ ] Allow for modding the UI
- [ ] Custom generation and dimensions
- [ ] Port Cactus ModLoader to Minecraft Java Edition
- [x] String ID system for items and blocks
- More...

## [Axo ModLoader](https://github.com/KaDerox/Axo-McLCE-ModLoader)
A mod loader

Currently supports only MinecraftConsoles(mods are .dll + manifest.json + textures, windows-only)

## [Faucet](https://github.com/ytsodacan/Faucet)
A mod loader for Minecraft Legacy Console Edition

Mods are `.dll`s written with FaucetSDK

Likely is slop; Supports MSVC+windows only


# Tools
- [Java-to-MLCE-Texture-Pack-Converter](https://github.com/ASAOddball1/Java-to-MLCE-Texture-Pack-Converter/blob/main/MLCE%20Converter.py) - slop


# Launchers

## [LCE-Qt-Launcher](https://github.com/xgui4/LCE-Qt-Launcher)
This is a free/libre MC LCE Launcher written in python and Qt with Freedom and GNU/Linux support in mind


Other launchers:
- [Legacy Console Launcher](https://github.com/OxyZin/LegacyConsoleLauncher) - C# + WinForms
- [Emerald Legacy Launcher](https://github.com/Emerald-Legacy-Launcher/Emerald-Legacy-Launcher) - sloppy, even though it is interesting
- [Flint](https://github.com/synomal/Flint) - smells like AI spirit

# Feel free to correct errors/typos!
