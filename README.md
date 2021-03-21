# Acheron Austin

![alt text](https://raw.githubusercontent.com/Gondolindrim/acheronLibrary/master/graphics/acheronReadme.png "Acheron Logo")

See [this page](https://gondolindrim.github.io/AcheronDocs/austin/intro.html) for the Austin PCB documentation.

## Introduction

The Austin is a fullsize compact keyboard featuring a variant of the 1800CP layout, designed by PheonixStarr and sold by DriftingMechanics. This repository features the Austin PCB source files.

## Technical information

- Layout size: fullsize compact
- Compatible switches: MX-like only, no hotswap capabilities
- Lighting: per-key single-color through-hole LEDs. Pre-Release Beta also has RGB underglow.
- Microcontroller: STM32F072(X)(Y)(Z), where:
  * x can be either 8 (64kB flash variant) or B (128kB flash variant)
  * Y can be either C (LQFP48 package) or U (UQFPFPN48 package)
  * Z can be either 6 or 7 (higher temperature grade)
- Connector: fixed USB Type C on the bottom side, no JST connector
- Firmware compatibility: QMK (with VIA support)
- Protection hardware:
  * USB data lines and power rail ESD suppressing
  * USB power overvoltage protection
  * Enclosure grounding pad
  * Overcurrent protection
  * LDO crowbar diode
  * EMI suppression (shielding ferrite bead)
- Current release: pre-Release Beta (has not been prototyped yet)
- Designer: Gondolindrim
- License: Acheron Open-Source Hardware License version 1.3

## Keyboard compatibility and availability

This PCB is designed to be made-to-fit the Austin keyboard and, as such, the only known compatible case is the Austin's. Also, the only known ways to obtain an Austin were through the [round one](https://geekhack.org/index.php?topic=102542.0) and [round two](https://geekhack.org/index.php?topic=106139.0) group buys, which are now closed and non-available.

## Acknowledgements

- The first prototypes of this PCB were paid for and tested by KeebsForAll, who also intends to make units of this PCB available for purchase.

- Geon, who kindly spent time helping design this PCB to fit his keyboards.

## Copyright notice

This project is released under the Acheron Open-Hardware License V1.3. For the license, please refer to the LICENCE.md file.

## Supported layouts

Click [this link](http://www.keyboard-layout-editor.com/#/gists/ba026fd3849cde8934be84d04b326c1d) for the KLE file for Austin.

![Austin layouts](https://github.com/Gondolindrim/Austin/raw/master/graphics/austinKLE.png)

## Copyright notice

This project is released under the Acheron Open-Hardware License V1.3. For the license, please refer to the LICENCE.md file.
