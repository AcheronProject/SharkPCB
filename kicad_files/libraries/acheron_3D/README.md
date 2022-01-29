# Acheron 3D KiCad footprint library

![alt text](https://raw.githubusercontent.com/Gondolindrim/acheronLibrary/master/graphics/acheronReadme.png "Acheron Logo")

## Introduction

Acheron 3D is the AcheronProject's KiCad footprint 3D models library for. Most of these models were obtained online; check the **Description and credits** section for the due credits.

## How to use

1. Clone the git repository into a ``libraries`` folder inside your KiCad project main folder, also known was ``${KIPRJMOD}``.
2. In PCBNEW, go into ``Preferences > Configure paths... `` then under the ``3D Search Paths`` section, add an alias called ``ACHERON_3D`` and set the path to the library you just downloaded.
3. After that the library footprints should be shown with their 3D step models in KiCAD's renders.

## Description and credit

- ``QFN-60_7x7mm_P0.4mm`` was copied from [Ultra Librarian's page](https://app.ultralibrarian.com/details/CA8B0F7C-78E3-11EA-8C00-0AD2C9526B44/ISSI/IS31FL3741-QFLS4-TR?ref=digikey) (last access march 25, 2021).
- ``DHN-02F`` was obtained from [3DCC's page](http://https://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=1024220) (last access july 27, 2021).
- ``811-22-`` are spring-loaded connector pins and their STEP models were optained directly from [Millmax's website](https://www.mill-max.com/) (last access january 21, 2022).

## Copyright notice

This project is released under the Acheron Open-Hardware License V1.3. For the license, please refer to the LICENCE.md file.

## Credits

- DFN-8 step file: https://www.3dcontentcentral.com/download-model.aspx?catalogid=171&id=602171. Last accessed july 09, 2021.
