# Acheron Components KiCad footprint library

![alt text](https://raw.githubusercontent.com/Gondolindrim/acheronLibrary/master/graphics/acheronReadme.png "Acheron Logo")

## Introduction

Acheron Components is the AcheronProject's KiCad footprint library for general footprints as resistors, ICs, capacitors, LEDs. Most of these footprints were developed as modifications of KiCad's default libraries, others were developed independently from datasheets.

## How to use

1. Clone the git repository into a ``libraries`` folder inside your KiCad project main folder, also known was ``${KIPRJMOD}``
2. In PCBNEW, go into ``Preferences > Manage Footprint Libraries... `` then under the Project tab, press the plus sign and select the ``acheron_Components.pretty`` folder.
3. After that the library footprints should be available for addition in the PCB layout from the ``Add a footprint`` button. Click that button or press O and try adding a footprint from the library like the ``D_THT_7.62mm`` footprint.

## Copyright notice

This project is released under the Acheron Open-Hardware License V1.3. For the license, please refer to the LICENCE.md file.
