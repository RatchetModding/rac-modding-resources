# rac-modding-resources


A list of useful resources when modding and/or reverse engineering any of the Ratchet and Clank games.

Might also be of use for other games that share engine code with these games.

Please note that some of the listed tools might be a Work in Progress.

*If you are writing a RaC specific guide for any of the listed tools or RaC modding in general, and want a centralized place to share these, please put your guide in the `guides` folder and include it in the list below.*


------------------

- List of resources
  - [Level editors](#level-editors)
  - [Savegame editors](#savegame-editors)
  - [File parsers and archive extractors](#file-parsers-and-archive-extractors)
  - [Spreadsheets with various info](#spreadsheets-with-various-info)
  - [Reverse engineering tools](#reverse-engineering-tools)
- [Legal stuff](#legal-stuff)


## Level editors

**[`^        back to top        ^`](#)**

These level editors are also a good code reference for the file formats used in the games.

 - [Replanetizer](https://github.com/game-fuckery-inc/replanetizer) - Level editor for the PS3 trilogy remasters.  `C#` `WinForms`
 - [RatchetLevelEditor](https://github.com/badger41/RatchetLevelEditor) - Previous level editor for the PS3 trilogy remasters. `C#` `WinForms`
 - [Wrench Editor](https://github.com/chaoticgd/wrench) - A set of modding tools for the PS2 games. `C++` `Dear ImGui`

## Savegame editors

**[`^        back to top        ^`](#)**

These savegame editors can also be a good resource for a list of value addresses as used in savegames.

 - [Slim's Editor](https://github.com/maikelwever/slimseditor) - A savegame editor for the Ratchet and Clank games. `Python 3` `Windows` `Linux` `Dear ImGui` `GPL-3.0`
 - [rac-savegame-editor](https://github.com/maikelwever/rac-savegame-editor) - Old version of the savegame editor for the Ratchet and Clank series of games (PS2, PS3, PSVita). `C#` `GTK3` `GPL-3.0`
 - [Ratchet and Clank Save Editor](https://www.nextgenupdate.com/forums/ps3-trophies-game-saves/718082-release-ratchet-clank-save-editor-all-1.html) ([Presumed source](https://github.com/primetime43/Playstation-3-Tools/tree/master/Ratchet%20%26%20Clank%20Into%20the%20Nexus%20Save%20Editor/Red-EyeX32%20-%20Test%20Drive%20Unlimited%202%20Save%20Editor)) - Save editor for all the Ratchet and Clanks `C#` `Winforms`
 - [RC-checksum](https://github.com/stiantoften/RC-checksum) - Ratchet & Clank save.bin checksum repair tool. `Cross-platform`


## File parsers and archive extractors

**[`^        back to top        ^`](#)**

 - [ig-tools](https://github.com/doesthisusername/ig-tools) - Tools for modding and reversing Ratchet & Clank (PS4) `Python` `C`
 - [PSArcFS](https://github.com/maikelwever/psarcfs) - A very crude and not very optimized FUSE handler for .psarc files. Supports ZLIB and LZMA compression. `Rust` `Linux` `GPL-3.0`
 - [PSARC reference and tools list](https://www.psdevwiki.com/ps3/PlayStation_archive_(PSARC)) - Doc about PSARC file format and links to tools for dealing with PSARC archives.
 - [wadutil](https://github.com/stiantoften/wadutil) - A utility to decompress Ratchet & Clank .wad files `C` `Cross-platform`
 - [rac-dvd-toc-parser](https://github.com/maikelwever/rac-dvd-toc-parser) - Simple Python script to get hidden files from PS2 disc image. `Python` `GPL-3.0`
 - [PIFconvert](https://github.com/stiantoften/PIFconvert/) - Converter/parser for PIF files from PS2 editions. `C` `Cross-platform`
 - [piftools](https://github.com/CreepNT/piftools) - Some tools to find and manipulate PIF images. `Python` `GPL-3.0`


## Spreadsheets with various info

**[`^        back to top        ^`](#)**

 - [Ratchet & Clank Series Addresses](https://docs.google.com/spreadsheets/d/1D1S7CEzhpDqT2QFFMuiF9rvWXvmR5ezt_UI2VxLOis8/preview) - A compilation of all relevant memory addresses for the Ratchet & Clank series 
 - [UYA savefile](https://docs.google.com/spreadsheets/d/1uZBCG_QkMCzCIdYgSZr1CfKIFTNrRYJrNMuQDCtAOWo/preview) - Addresses and structure info for UYA savegame files
 - [Ratchet & Clank Builds](https://docs.google.com/spreadsheets/d/14mnYKrPg_CNHNAB2XL0ceJHiN4-S4jmi39-0R4ahkCs/preview) - List of known release builds of various versions of the games.
 - [Ratchet & Clank Prototype builds](https://docs.google.com/spreadsheets/d/1y_zZC4bDOvKGI8SWXpOORkBiJSqBKwhWEsRI-NtMToo/preview) - Spreadsheet containing Prototype builds and their estimated build dates
 - [Model IDs](https://docs.google.com/spreadsheets/d/1RA_VpE__IFksQz-EPsav-V0Tfpq9-fiHoZBNeX0JkAo/preview) - Spreadsheet with Model IDs


## Reverse engineering tools

**[`^        back to top        ^`](#)**

 - [List of reverse engineering resources](https://github.com/wtsxDev/reverse-engineering) - A curated list of awesome reversing resources.
 - [Ghidra](https://github.com/NationalSecurityAgency/ghidra) - A software reverse engineering (SRE) framework. `Cross-platform` `Apache-2.0`
    - [Ghidra Emotion Engine plugin](https://github.com/beardypig/ghidra-emotionengine) - Ghidra support plugin for the PS2's Emotion Engine.
    - [Ghidra PS3 scripts](https://github.com/zecoxao/ps3_ghidra) - A collection of scripts/loaders/plugins for ghidra used to aid ps3 reverse engineering.
 - [PCSX2](https://pcsx2.net/) ([Source code](https://github.com/PCSX2/pcsx2)) - A free and open-source PlayStation 2 (PS2) emulator, with debugger. `Windows` `Linux` `GPL-2.0`
 - [RPCS3](https://rpcs3.net/) ([Source code](https://github.com/RPCS3/rpcs3)) - The world's first free and open-source PlayStation 3 emulator/debugger. `Windows` `Linux` `GPL-2.0`
 - [Cheat Engine](https://www.cheatengine.org/) ([Source code](https://github.com/cheat-engine/cheat-engine/)) - A development environment focused on modding games and applications for personal use. `Windows` `LGPL-2.0`
 - [Scanmem & Game Conqueror](https://github.com/scanmem/scanmem) - A debugging utility and GUI designed to isolate the address of an arbitrary variable in an executing process. `Linux` `GPL-3.0` 



# Legal stuff

All mentioned trademarks are property of their respective owners.

This project is public domain under the [Creative Commons Zero v1.0 Universal](LICENSE) license.
