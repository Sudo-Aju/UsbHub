<div align="center">

# USB Hub

### A custom USB hub designed from scratch using a custom PCB, USB-C connectivity, and a 3D-printed enclosure.

<img src="https://github.com/user-attachments/assets/98bfa959-2a49-4520-9d16-db6c9485f56c" width="650">

<br>

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![PCB](https://img.shields.io/badge/PCB-Custom-blue?style=for-the-badge)
![USB](https://img.shields.io/badge/USB-USB--C-green?style=for-the-badge)
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-orange?style=for-the-badge)

</div>

---

# Overview

This project is a **fully custom USB hub** built from the ground up, combining PCB design, electronics, CAD modeling, and assembly into a compact desktop accessory.

Instead of relying on an off-the-shelf hub, every aspect—from the schematic and PCB layout to the enclosure—was designed to better understand USB hardware while creating a practical device for everyday use.

---

# Features

* Custom PCB
* USB-C input
* Multiple USB output ports
* Compact desktop form factor
* 3D-printed enclosure
* Clean internal wiring
* Designed for easy assembly
* Fully reproducible using the provided design files

---

# Hardware

| Component          | Specification    |
| ------------------ | ---------------- |
| USB Hub IC         | CoreChips SL2.1S |
| Input              | USB-C            |
| Outputs            | USB-C + USB-A    |
| PCB                | Custom FR4 PCB   |
| Enclosure          | 3D Printed       |
| Passive Components | 0603 SMD         |

---

# Project Images

<p align="center">

<img src="https://github.com/user-attachments/assets/98bfa959-2a49-4520-9d16-db6c9485f56c" width="45%">
<img src="https://github.com/user-attachments/assets/9add08d4-e24f-468a-8bef-c4ac3cd752c4" width="45%">

<img src="https://github.com/user-attachments/assets/54588be4-992e-43e1-b737-f6ed21ac811b" width="45%">

</p>

---

# Zine Page

This project was also documented as part of a Hack Club **Zine**, summarizing the design process, hardware decisions, PCB layout, and final build in a single-page publication.

<p align="center">

<img src="https://github.com/user-attachments/assets/cccb0596-d946-43d7-b901-79098fc07dee" width="650">

</p>

---

# PCB Design

### PCB Layout

<p align="center">

<img src="https://github.com/user-attachments/assets/fbff16f3-9332-4069-90a8-eeb76eb7be79" width="90%">

</p>

### 3D PCB Render

<p align="center">

<img src="https://github.com/user-attachments/assets/69275e06-3abe-4b69-83f9-44bf7446e15f" width="90%">

</p>

---

# Bill of Materials

| Part                   | Qty | Description         |
| ---------------------- | --: | ------------------- |
| 1µF Capacitor (0603)   |   8 | Power filtering     |
| 100nF Capacitor (0603) |   3 | Decoupling          |
| 5.1kΩ Resistor (0603)  |   6 | USB-C Configuration |
| CoreChips SL2.1S       |   1 | USB Hub Controller  |
| USB-C Connector        |   3 | Input/Output Ports  |
| USB-A Connector        |   2 | Output Ports        |

---

# How It Works

1. Connect the hub to your computer using the USB-C input.
2. Plug peripherals into any available USB port.
3. The SL2.1S hub controller manages communication between the host and connected devices, allowing multiple USB devices to operate simultaneously.

---

# Why I Built It

I wanted to understand how USB hubs work beyond simply using one. Designing the PCB, selecting components, routing high-speed USB traces, and creating a custom enclosure challenged me to build a complete hardware product from scratch.

This project strengthened my understanding of:

* PCB design
* USB communication
* Electronics assembly
* CAD modeling
* Hardware prototyping
* Product design workflow

---

# Acknowledgements

This project was inspired by the **Stasis** starter guide from **Hack Club**, while all hardware design, PCB layout, enclosure design, and assembly were completed as part of this custom implementation.

---

<div align="center">

### Designed, assembled, and documented from scratch.

</div>
