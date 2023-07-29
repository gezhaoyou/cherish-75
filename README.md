## Cherish-75

<p align="left">
  <a href="./README.md">English</a> |
  <a href="./README_CN.md">简体中文</a>
</p>

Cherish-75 is a customized mechanical keyboard featuring a Gasket structure, with its PCB already verified through prototyping.

* License: MIT – Free to use and modify.
* Controller: STM32F072CBT6, with a separate Type-C subboard ensuring soft elasticity.
* PCB: Slotted PCB design with optional solder mask opening (gold plating available). See [Link](https://oshwhub.com/caiyahoho/Cherish-75) for the LCSC project.
* Layout: 75% size, Fang tooth arrangement.
* Switch: Supports both soldering and hot-swappable switches.
* RGB: Features an RGB SMD LED beneath the Caps Lock key.
* Firmware: Compatible with QMK & VIA. Refer to the [fireware] directory for details.
* Case: 3D printed design with magnetic top and bottom covers. Check the [3d-model] directory for designs.

```bash
├── case-and-plate
│   ├── top-case-with-X.stl 
│   ├── top-case.stl
│   ├── bottom-case.stl
│   ├── slotted-plate.dwg
│   └── plate.dxf
├── firmware
│   ├── bin  
│   └── cherish-75-via.json # Via Config
├── hardware
│   ├── bom.xlsx # BOM
│   └── gerber # PCB  Gerber 
```

## PCB
### Black
![top](./imgs/top.png)

![bottom](./imgs/bottom.png)

### White:
![top](./imgs/white-top.png)

![bottom](./imgs/white-bottom.png)

### Daughterboard

![daughterboard](./imgs/daughterboard-1.png)

![daughterboard](./imgs/daughterboard-2.png)

## Layout

![layout](./imgs/layout.png)

**Via**
![layout](./imgs/cherish-75-via.png)

## Case
### Top Case, Style 1


![top-case](./imgs/top-case.png)


### Top Case, Style 2

![top-case-x](./imgs/top-case-x.png)

![top-case-x](./imgs/top-case-x-2.png)

### Overview

![top-case](./imgs/3d-1.png)

![top-case](./imgs/3d-2.png)

## Physical
### PCB 

![pic-3](./imgs/pcb-3.jpg)

![pic-4](./imgs/pcb-4.jpg)
 
![pic](./imgs/pcb-1.jpg)

### Keyboard
![pic](./imgs/bd-1.jpg)

### Video
**BiliBili**

[![bilibili](https://res.cloudinary.com/marcomontalbano/image/upload/v1717640150/video_to_markdown/images/youtube--ES9FB7N3KS8-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.bilibili.com/video/BV1CS4y1W7Da/)
 
**Youtube**
[![Cherish-75](https://res.cloudinary.com/marcomontalbano/image/upload/v1717640150/video_to_markdown/images/youtube--ES9FB7N3KS8-c05b58ac6eb4c4700831b2b3070cd403.jpg)](https://www.youtube.com/watch?v=ES9FB7N3KS8&t=7s "Cherish-75")