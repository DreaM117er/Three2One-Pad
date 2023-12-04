# Three2One Pad

![](pic/rp0.jpg)

## Description

### What is 321 Pad?

Three2One Pad is a small keyboard pad for persional function keys. It supported maxium 12 keyboard keys or 8 keyboard keys + 4 rotray encoder, MX switches hotswap, and used RP2040 mini series micro controller (ex. supermini/zero... etc) to drive.

This is a simple repostiory, it would be opensource all files on here, check files inside floder.

### Layout and Keymap

![](pic/layout.png)
![](pic/vial.png)
c

## PCB & 3D module

|![](pic/info0.png)|![](pic/info1.png)|
|---|---|
|![](pic/info-p1.png)|![](pic/info-p2.png)|

## Building Guide

### Material

|Item|Amount|Note|
|---|---|---|
|PCB|1|-|
|MCU|1|RP2040 SuperMini/Zero|
|Cases|1|Acrylic or 3DP|
|Hotswap Socket|8-12|MX version|
|Diodes 1N4148|12|SOD-123 or DO-35 version|
|M2x5mm Screw|12|for Arcylic case|
|M2x6mm Spacer|6|for Arcylic case|
|Rotray Encoder EC-11|1-4|Personal Option|
|Rubber feets|4|ø8mm, H1mm|

### Guide.1: PCB part

- Prepare hotswap sockets and solder gun, you need to install them first.

![](pic/01.jpg)

- Then install diodes to PCB.

![](pic/02.jpg)
![](pic/03.jpg)

- Cut off useless diode feets after solder 1N4148 diodes.

![](pic/04.jpg)

- If you finished solder diodes, next way is install MCU.

![](pic/05.jpg)

- Install pin header to PCB then put MCU on top of headers.

![](pic/06.jpg)
![](pic/07.jpg)
![](pic/08.jpg)

- Rotray Encoders are persional option. If you want to install them, please decide to install 0-4 EC-11(s) on the PCB.

![](pic/09.jpg)

- Last step flash firmware and test how's the pad working.

![](pic/10.jpg)

> **Note**
>
> RP2040 SuperMini/Zero have same bootloader way, you need to keep pushing switch on the MCU before plug USB-C cable to the PC. After that, you can see a disk on your device, then put .uf2 firmware file into disk.

### Guide.2: Case part

- First install spacers on PCB and bottom case.

![](pic/12.jpg)
![](pic/11.jpg)

- Put the PCB on bottom case, then install plate and cover.

![](pic/13.jpg)
![](pic/14.jpg)
![](pic/15.jpg)
![](pic/16.jpg)
![](pic/17.jpg)

- If you finish case installed, put 4 rubber feets below the bottom case.

![](pic/18.jpg)
![](pic/19.jpg)

- Last step, put MX switches and keycaps on the pad.

![](pic/20.jpg)

- Done.

![](pic/rp0.jpg)

## Informations and Special Thanks

- [QMK Firmware](https://qmk.fm/).
- [VIAL](https://get.vial.today/).
- [KiCAD](https://www.kicad.org/) version 7.0.5.
- [JLCPCB](https://jlcpcb.com/).
- [AutoDesk Fusion360](https://www.autodesk.com/products/fusion-360/free-trial).
- Taiwan [Tatung University](https://www.ttu.edu.tw/) - [Department of Mechanical and Materials Engineering](https://mme.ttu.edu.tw/)
- And my friend: [YCT](https://github.com/yct38)