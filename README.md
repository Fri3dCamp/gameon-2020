# Fri3d GameOn 2020

This repository contains the hardware design of the [Fri3d Camp](https://fri3d.be/) GameOn that connects to the [badge](https://github.com/Fri3dCamp/badge-2020).
The board consists our of a joystick, some buttons, a Micro SD card slot and a small 1W audio amplifier.
The project progress can be followed on our [Hackaday.io](https://hackaday.io/project/183766-gameon) page.

## Blockdiagram

In order to make the documentation easier to use, we've added the block diagram in this repository.

![GameOn Block Diagram](media/GameOn_Block.png)

## REV 00
First prototype to verify the schematic design.

![GameOn Front 00](media/GameOn_00_FRONT.jpg)

![GameOn Back 00](media/GameOn_00_BACK.jpg)

## REV 01
Modified the pinout for the new hardware revision of the badge.

## REV 02
Production version of the GameOn. 

Note that the Start button, connected to the [badge](https://github.com/Fri3dCamp/badge-2020) IO pin 32, is active high whilst all other buttons are active low.
