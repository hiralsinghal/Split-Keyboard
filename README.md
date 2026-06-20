# Split-Keyboard
A split-keyboard made for ergnomic comfort. It has 42 keys, each side having 21. XIAO-nRF5280 is the MCU powering the project because of its wireless support.

## Features

- Wireless
- XIAO-nRF52840 is the MCU.
- 42 keys

## Schematic

You have draw hierarchical sheets and set the sheetname respectly whereas the sheet file should be named the same for both so that whatever symbols you place in one of them are copied into the other without you switching sheets constantly. This wouldnt impact the way footprints are imported into the PCB editor.

![schematic](assets/schematic.png)

### Left Side

![left side schematic](assets/left-schematic.png)

### Right Side

![right side schematic](assets/right-schematic.png)

## PCB

The source files are in the PCB folder.

![pcb](assets/pcb.png)

## Case

This was made in Fusion, using the PCB as reference. It has cutouts for switches, keys and XIAO ports. The source file can be found in the folder CAD.

1[case](assets/case.png)

### Left

This is the case for the left side of the keyboard.

![left-keyboard](assets/left-side-case.png)

### Right

This is the case for the right side of the keyboard.

![right-keyboard](assets/right-side-case.png)

## Firmware

It uses ZMK firmware because of its support for split keyboards. Each controller runs their own firmware but they make it work as a single device. The files are in the firmware folder.

## Zine

This was made in Figma. I enjoyed making it kinda.

![zine](assets/zine.png)


## Why did I make it?

I made it cause it seemed like a cool project. The routing was tough ngl. Each footprint alligned differently and so many switches and diodes. Its like each project is improving my skills consistently. I now know how to route better (kinda) This was made for [Fallout](fallout.hackclub.com).