# Acheron Hardware KiCad footprint library

![alt text](https://raw.githubusercontent.com/Gondolindrim/acheronLibrary/master/graphics/acheronReadme.png "Acheron Logo")

## Introduction

Acheron Hardware is the AcheronProject's KiCad footprint library for overal interaction hardware like standoffs, featherboards, buttons, battery holders. Most of these footprints were developed independently using datasheets.

## How to use

1. Clone the git repository into a ``libraries`` folder inside your KiCad project main folder, also known was ``${KIPRJMOD}``.
2. In PCBNEW, go into ``Preferences > Manage Footprint Libraries... `` then under the Project tab, press the plus sign and select the ``acheron_Hardware.pretty`` folder.
3. After that the library footprints should be available for addition in the PCB layout from the ``Add a footprint`` button. Click that button or press O and try adding a footprint from the library like the ``Mini_F4X1_STM32`` footprint.

## Description and credits

- ``Bluepill_STM32F103``: Blue-Pill style featherboard (STM32F103-based). It was developed independently;
- ``Mini_F4X1_STM32``: "black-pill" style featherboard (STM32F4X1-based), specifically the ones [developed by WeAct](https://github.com/WeActTC/MiniSTM32F4x1). They were developed using the openly available land footprint in the hardware documentation section of the repository;
- ``MouseBite_IPC7351``: mouse bite marks as defined in IPC standard 7351 for PCB reproduction and pannelization.

## Copyright notice

This project is released under the Acheron Open-Hardware License V1.3. For the license, please refer to the LICENCE.md file.
