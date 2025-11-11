# AoC-More-Speed-Options
Adds a varied set of default speed options and comes with a customizable config so you can add your own.

Default values: 0.1f, 0.25f, 0.5f, 1f, 1.5f, 2f, 2.5f, 3f, 5f, 10f
Vanilla is 0.5f, 1f, 1.5f, 2f, 3f, 5f

## Requirements
- BepInEx 5 x64 (Mono). Download from the official BepInEx releases. https://github.com/bepinex/bepinex/releases

## Install
1. Extract the BepInEx zip into the game folder (next to the exe). Run the game once.
2. Extract **this mod’s zip** into the plugins location so that:
   - BepInEx\plugins\More Speed Options.dll exists
3. Run the game. Check `BepInEx/LogOutput.log` for "More Speed Options loaded".

## Configure
After the first launch with the plugin installed you can find the created config in BepInEx/config/MoreSpeedOptions.cfg. Config includes directions. Add as many speeds as you want. Just always have at least 3 and make sure the starting option isn't the first or last!
