# SnapLEDGrid# PixelSnapGrid

A modular 6x6 Neopixel LED tile system with magnetic edge connectors and a Seeed Studio RP2040 controller. Each tile snaps together to create dynamic, scalable LED displays.

## 🔧 Features
- 6x6 Neopixel grid (THT)
- Magnetic edge connectors for power + data passthrough
- Powered by Seeed Studio RP2040
- Programmed using Arduino
- Designed in KiCad

## 🧰 Repo Structure

- `Firmware/` – Arduino code for driving the panels
- `Hardware/` – KiCad schematics, PCB layouts, and BOM
- `Images/` – Photos and renders of the project
- `Docs/` – Build instructions, wiring, and expansion info

## 📸 Preview

<img src="Images/assembled_tile.jpg" width="400"/>
<img src="Images/pcb_top_render.png" width="400"/>

## 🚀 Getting Started

Flash the `pixel_snap.ino` sketch using the Arduino IDE with the RP2040 board selected. Daisy-chain additional panels via the magnetic connectors.

## 🔌 Pin Mapping

| Function     | RP2040 Pin |
|--------------|------------|
| Data In      | GPIOX      |
| Data Out     | GPIOY      |
| Power/GND    | VIN / GND  |

