LiDAR GTA V
============================
*A plugin for Grand Theft Auto V that generates a labeled LiDAR point cloud form the game environment.*

<img src="/samples/LiDAR Sample - Traffic.png">

## Requirements

* [Grand Theft Auto V](https://store.steampowered.com/app/271590/Grand_Theft_Auto_V/)
* [ScriptHookV by Alexander Blade](http://www.dev-c.com/gtav/scripthookv/)

## Installation

1. Install [ScriptHookV](http://www.dev-c.com/gtav/scripthookv/) following its accompanying instructions.
2. Copy-paste *LiDAR GTA V.asi* and the *LiDAR GTA V* folder found in [*bin/Release*](https://github.com/UsmanJafri/LiDAR-GTA-V/tree/master/LiDAR%20GTA%20V/bin/Release) into your GTA-V directory (the folder containing *GTAV.exe*)

## How to use

1. Navigate to *#your_game_directory#/LiDAR GTA V/LIDAR GTA V.cfg* and edit the parameters as needed. The parameters include: Horizontal FOV, Vertical FOV, Range, Density and Output Filename.
2. Startup GTAV in a story mode.
3. Press V to cycle through camera modes until first person mode is enabled.
4. Press F6 to generate a LiDAR point cloud of the world.
5. Output file is located under *#game_directory#/LiDAR GTA V/#your_chosen_filename#.ply*
6. The output is a Polygon File Format (.PLY) file containing only vertex data.
7. Vertex Color Code:

| Vertex Color | Label |
|---|---|
| Red | Vehicle |
| Green | Humans and Animals |
| Blue | Game props |
| White | Road, Buildings and other hitable textures |
| Black | No hit |

## Contributing

* You will need Visual Studio 2017 or higher to open the project.
* Any contributions to the project are welcomed, it's recommended to use GitHub [Pull requests](https://help.github.com/articles/using-pull-requests/).

## Acknowledgements

* [Native Trainer](http://www.dev-c.com/gtav/scripthookv/) (a ScriptHookV sample) was used as base project to import configuration.

## Samples

<img src="/samples/LiDAR Sample - Michael Home.png">

<img src="/samples/LiDAR Sample - Test Area.png">

<img src="/samples/LiDAR Sample - Traffic.png">
