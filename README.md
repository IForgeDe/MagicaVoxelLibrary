# MagicaVoxelLibrary

A library of models created with [MagicaVoxel](https://ephtracy.github.io/).

## Setup MagicaVoxel

After cloning this repository, open the file `config/config.txt` of your MagicaVoxel setup.
Modify the two values of `dir_model` and `dir_pattern` from the default `[[$/vox]]` to `[[$/{RelativePathToYourRepositoryUrl}/Models]]`.
Note that you need to adjust the `{RelativePathToYourRepositoryUrl}` value to fit your folder structure.
Open MagicaVoxel and the project view should show you the content of this MagicaVoxelLibrary.

## Brick definitions

### LEGO-System

There are 2 different definitions of a LEGO-System brick for the MagicaVoxelLibrary.

* LD (Low density) for 1 brick equals 1 voxel
* MD (Medium density) for 1 brick equals 2 \* 2 \* 3 (width \* depth \* height) voxel
