# SharkPCB project

This is a project to make a freely available, open-source 40% keyboard Printed Circuit Board (PCB). The board is compatible with Planck plates and cases and supports three layouts: full grid, 1x2U spacebar and 2x2U spacebar.

The gerber files also contain a plate file, from which a plate can be made of FR4 (the same material as the circuit board) in the same factory as the PCB itself.

# Board preview (version 2.2.1)

![Alt text](boardPreview.png)

This project is licensed under the Creative Commons Non-Commercial Share-Alike 4.0 license, available in (https://creativecommons.org/licenses/by-nc-sa/4.0/).

# Changelog and version control

## **12/01/19 (V3.0.1)**:

Started porting the version 2 from the ATMEGA32U4 processor to a more modern Cortex M4 STM32F303CCT6 processor

## **13/01/19 (V3.0.2)**:

Added USBC connector

## **14/01/19 (V3.0.3)**:

Added RGB underglow with the WS2812B

## **15/01/19 (V3.0.3)**:

Changed the grid used from the standard 19.05mm to the 19mm used in the Planck

# To-do list
- [ ] Finish the porting to STM32 (as suggested by Walkerstop from GH)
- [ ] Change the grid from 19.05mm (3/4΅) to 19mm as the Planck does (as suggested by garbo from GH)
- [x] Add RGB underglow support
- [ ] Finish THT design
- [ ] Prototype SMD design
- [ ] Prototype THT design
