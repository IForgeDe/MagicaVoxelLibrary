# MagicaVoxelLibrary

A library of models created with [MagicaVoxel](https://ephtracy.github.io/).

## Setup MagicaVoxel

After cloning this repository, open the file `config/config.txt` of your MagicaVoxel setup.
Modify the two values of `dir_model` and `dir_pattern` from the default `[[$/vox]]` to `[[$/{RelativePathToYourRepositoryUrl}]]`.
Note that you need to adjust the `{RelativePathToYourRepositoryUrl}` value to fit your folder structure.
Open MagicaVoxel and the project view should show you the content of this MagicaVoxelLibrary.

## Folder structure

The folder structure defines a folder for each working space.
If you want to work only in a special space, it is recommend to modify your MagicaVoxel setup, that the `dir_model` and `dir_pattern` variables point to the relevant folders.
For example, if you want to work only in the medium density `LEGO-System` space, the `dir_model` variable should defined to `[[$/{RelativePathToYourRepositoryUrl}/LEGO-System/MD]]` and the `dir_pattern` variable to `[[$/{RelativePathToYourRepositoryUrl}/LEGO-System/MD/Patterns]]`.

## File structure

### LEGO

The filename for a lego MagicaVoxelLibrary file must start with the setnummber followed by a hyphen followed by the density definition.

## Brick definitions

### LEGO-System

There are 2 different definitions of a LEGO-System brick for the MagicaVoxelLibrary.

* LD (Low density) for 1 brick equals 1 voxel
* MD (Medium density) for 1 brick equals 2 \* 2 \* 3 (width \* depth \* height) voxels
