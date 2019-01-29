# SharkPCB project

This is a project to make a freely available, open-source 40% keyboard Printed Circuit Board (PCB). The board is compatible with Planck plates and cases and supports three layouts: full grid, 1x2U spacebar and 2x2U spacebar.

The gerber files also contain a plate file, from which a plate can be made of FR4 (the same material as the circuit board) in the same factory as the PCB itself.

# Board preview (version 3.0.6)

![Alt text](./renders/frontRender.png)

![Alt text](./renders/backRender.png)

This project is licensed under the Creative Commons Non-Commercial Share-Alike 4.0 license, available in (https://creativecommons.org/licenses/by-nc-sa/4.0/).

# Changelog and version control

## **2019/01/12 (V3.0.1)**:

Started porting the version 2 from the ATMEGA32U4 processor to a more modern Cortex M4 STM32F303CCT6 processor

## **2019/01/13 (V3.0.2)**:

Added USBC connector

## **2019/01/14 (V3.0.3)**:

Added RGB underglow with the WS2812B

## **2019/01/15 (V3.0.4)**:

Changed the grid used from the standard 19.05mm to the 19mm used in the Planck

## **2019/01/21 (V3.0.5)**:

Solved a problem with connector wiring and added a nice render to the README

## **2019/01/26 (V3.0.6)**

Changed components to SMD.

Added Blender renders.

Updated preview.


# To-do list
- [x] Finish the porting to STM32 (as suggested by Walkerstop from GH)
- [x] Change the grid from 19.05mm (3/4΅) to 19mm as the Planck does (as suggested by garbo from GH)
- [x] Add RGB underglow support
- [ ] Finish SMD design
- [ ] Finish THT design
- [ ] Prototype SMD design
- [ ] Prototype THT design
