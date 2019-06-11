# GPU switching script for Linux

## Description
It can turn on/off your discrete GPU for compute without graphics, without running the program with optirun. It also does not start another X server, like optirun does. It is ideal if you want to use your GPU only for CUDA compute.

## Setup
You need to have bumblebee installed in order for this to work. For more details on how to set it up, see https://wiki.archlinux.org/index.php/bumblebee.

Copy the file "gpu" in your path and change it's permission with chmod +x.

## Usage

To turn on Nvidia GPU, use:
```
gpu on
```
To trun it off, run:
```
gpu off
```
Note: you can only turn it off if nothing is using it.

To see whether the GPU is on or off, run the tool without arguments:

```
gpu
```
