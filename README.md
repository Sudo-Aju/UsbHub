
# USB Hub Project

## What is this project?

This is a custom-designed USB hub built from scratch, combining hardware design, wiring, and assembly into a single functional device. The goal of this project is to create a clean, compact, and reliable USB hub that can connect multiple devices efficiently.

## What does it do?

This USB hub allows multiple USB devices to connect to a single port. It is designed to be practical, easy to use, and structurally solid with proper component placement and assembly.

## Why did I make this project?

I created this project to understand how USB hubs work at a deeper level and to challenge myself to build a complete hardware product from scratch. Instead of using a ready-made solution, I wanted to design something original that solves the everyday problem of limited USB ports while also improving my skills in electronics, CAD design, and system assembly.

## Project Images


![USB Hub Photo 1](https://github.com/user-attachments/assets/98bfa959-2a49-4520-9d16-db6c9485f56c)
![USB Hub Photo 1](https://github.com/user-attachments/assets/9add08d4-e24f-468a-8bef-c4ac3cd752c4)
![USB Hub Photo 1](https://github.com/user-attachments/assets/54588be4-992e-43e1-b737-f6ed21ac811b)


<img width="1587" height="2245" alt="Zin1" src="https://github.com/user-attachments/assets/cccb0596-d946-43d7-b901-79098fc07dee" />



<img width="1968" height="1613" alt="Screenshot 2026-06-01 at 12 24 28" src="https://github.com/user-attachments/assets/fbff16f3-9332-4069-90a8-eeb76eb7be79" />

<img width="2436" height="1720" alt="Screenshot 2026-05-31 at 10 50 26" src="https://github.com/user-attachments/assets/69275e06-3abe-4b69-83f9-44bf7446e15f" />


## BOM

|No.|Quantity|Comment              |Designator              |Footprint                       |Value|Manufacturer Part    |Manufacturer   |Supplier Part|Supplier|Link                                                  |
|---|--------|---------------------|------------------------|--------------------------------|-----|---------------------|---------------|-------------|--------|------------------------------------------------------|
|1  |8       |1uF                  |C1,C2,C3,C4,C5,C8,C9,C13|C0603                           |1uF  |                     |               |             |        |https://www.lcsc.com/search?q=1uF%200603%20capacitor  |
|2  |3       |100nF                |C10,C11,C12             |C0603                           |100nF|                     |               |             |        |https://www.lcsc.com/search?q=100nF%200603%20capacitor|
|3  |6       |5.1K                 |R1,R2,R3,R4,R5,R6       |R0603                           |5.1K |                     |               |             |        |https://www.lcsc.com/search?q=5.1k%200603%20resistor  |
|4  |1       |SL2.1s               |U1                      |SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL|     |SL2.1s               |CoreChips(和芯润德)|C2684433     |LCSC    |https://www.lcsc.com/product-detail/C2684433.html     |
|5  |3       |TYPE-C 16PIN 2MD(073)|USB1,USB4,USB5          |USB-C-SMD_TYPE-C-6PIN-2MD-073   |     |TYPE-C 16PIN 2MD(073)|SHOU HAN(首韩)   |C2765186     |LCSC    |https://www.lcsc.com/product-detail/C2765186.html     |
|6  |2       |10.0 QHHTZB6.3       |USB2,USB3               |USB-A-TH_10.0QHHTZB6.3          |     |10.0 QHHTZB6.3       |SHOU HAN(首韩)   |C668591      |LCSC    |https://www.lcsc.com/product-detail/C668591.html      |

## How to use

1. Connect the USB hub to your computer using the main input cable.
2. Plug your USB devices into the available ports.
3. Use your devices as usual; the hub distributes connectivity, allowing multiple devices to function simultaneously.

## Motivation and projetc completeness

This project includes a full design with all components, a clear structure for assembly, and a working concept. The design is inspired by the starter guide from Stasis by Hack Club and aims to be reproducible by others using the provided files and instructions.
