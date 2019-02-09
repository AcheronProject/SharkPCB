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

# Bill of Materials

In the ./bom/ folder there is an .xlsx file that can be uploaded directly into the LCSC site. The file contains all LCSC part numbers, quantities and descriptions. 

If you don't want to order them from LCSC, the table below can be used.

| Description  | Quantity |
| ------------- | ------------- |
| USB Connector TYPE-C-31-M-12  | 1 |
| C1 and C2 (22pF 0805)  | 2  |
| C7, C9, CRST1, CRST2 (4.7nF 0805)	| 4| 
| Fuse 0805 1.5A trip	| 1| 
| R5 and R6 (1MOhm 1206)	| 2| 
| Q1 (AO4406AL MOSFet)	| 1| 
| CSin1, CSout1, CVBus1-3 (100nF 0805)	| 5| 
| CVBus4 (1uF 0805)	| 1| 
| CVBus5 (4.7uF 0805)	| 1| 
| DF1 (RB060M-60TR SOD-123 Shottky Diode)	| 1| 
| QRST (NPN SOT-23 BJT)	| 1| 
| RCC (5.1kOhm 1206)	| 1| 
| RD+ and RD- (22ROhm 1206)	| 2| 
| RD+Up (1.5kOhm 1206)	| 1| 
| RPGate (10kOhm 1206)	| 1| 
| RRST (100kOhm 1206)	| 1| 
| RSGate1 (1kOhm 1206)	| 1| 
| SWRST1 (SMD Push Button)	| 1| 
| U1 (ARM STM32F303CCT6 processor)	| 1| 
| U2 (MCP1700-330 SOT23 3.3V LDO)	| 1| 
| Y1 (8MHz 4 pin SMD Crystal)	| 1| 
| RGB (WS2812B RGB Led Resistors)	| 8| 
| RL1-RL (360 Ohm 1206)	| 50| 
| D1-48, DS1 and DRST (1N4148W SOD123)	| 52| 


# To-do list
- [x] Finish the porting to STM32 (as suggested by Walkerstop from GH)
- [x] Change the grid from 19.05mm (3/4΅) to 19mm as the Planck does (as suggested by garbo from GH)
- [x] Add RGB underglow support
- [x] Finish SMD design
- [ ] Finish THT design
- [ ] Sent SMD design to fabrication
- [ ] Prototype SMD design
- [ ] Sent THT design to fabrication
- [ ] Prototype THT design
