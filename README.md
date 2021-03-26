# stronghold-mapeditortools
Map Editor Tool Set for Stronghold (in the future) and Stronghold Crusader

## Features
Make your custom maps symmetrical by mirroring every action in the map editor.

## Installation instructions
1. Download the correct files for your version of Stronghold (currently only Stronghold Crusader 1.41 is supported)
2. Rename the existing `binkw32.dll` in your game folder to `binkw32_real.dll`
3. Move the files from the zip file (`binkw32.dll, lua54.dll, shc-mapeditortools.lua`) to your game folder

## Usage instructions
When starting up the game, you will get your normal game window, and an extra console window. You can run LUA code in this console window. Type `help` to see the instructions for changing the active mirror mode and more.

## Modification instructions
To modify the way mirroring is done, modify the `shc-mapeditortools.lua` file.

## Copyright
```
Copyright Edward Gynt - All Rights Reserved
Written by Edward Gynt <gynt@users.noreply.github.com>, March 2021
```
