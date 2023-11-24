This repository contains mods that offer minor quality-of-life improvements over the base game of Cities: Skylines II.

**Disclaimer: These modifications are generally small but highly experimental. Your game may crash more frequently, and your save files could be corrupted.**

## Mods

Improves pedestrian pathfinding so they will be less likely to cross at "unsafe" areas (IE, areas where a crosswalk was removed, requiring them to cross to the opposite side first, or maybe use a nearby bridge) (Compatible with version 1.0.14f1)

## Installation

1. Install [BepInEx 5](https://github.com/BepInEx/BepInEx/releases)

   * Download `BepInEx_x64_5.4.22.0.zip` (or a newer version) and unzip all contents into the game's installation directory, typically `C:/Program Files (x86)/Steam/steamapps/common/Cities Skylines II`

   * The installation directory should now include the `BepInEx` folder, `doorstop_config.ini`, `winhttp.dll`

2. Download DLL files from the [release page](https://github.com/slyh/Cities2-Various-Mods/releases) and place them in the `Cities Skylines II/BepInEx/plugins` folder

3. Launch the game, mods should be loaded automatically.

## Thanks

[slyh/Cities2-Various-Mods](https://github.com/slyh/Cities2-Various-Mods/): Mod that I based this off

[Cities2Modding](https://github.com/optimus-code/Cities2Modding): Info dump / guides for Cities Skylines 2 modding

[BepInEx](https://github.com/BepInEx/BepInEx): Unity / XNA game patcher and plugin framework

[Harmony](https://github.com/pardeike/Harmony): A library for patching, replacing and decorating .NET and Mono methods during runtime