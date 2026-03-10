# ATmega328P Data Logger

A standalone MCU-based Data Logger PCB designed using KiCad.

## Overview
This board is built around the ATmega328P-AU microcontroller
and is designed to log data from external sensors via I2C,
storing it in onboard EEPROM memory.

## Components
| Component | Description |
|-----------|-------------|
| ATmega328P-AU | Main Microcontroller |
| 24LC1025 x2 | I2C EEPROM (Data Storage) |
| 32.768 KHz Crystal | Real-Time Clock |
| 16MHz Crystal | MCU Clock |
| BT1 | Battery Backup (RTC) |
| D1, D2 | Status LEDs |

## Interfaces
- **ICSP** — For programming the MCU
- **I2C** — Connect external sensors
- **UART** — Serial communication (TX/RX)
- **GPIO** — Pins 2-8 exposed for general use

## Files
- Schematic (PDF)
- 3D View (PNG)
- Gerber Files

## Tools Used
- KiCad

## Status
Design Complete

## 3D View
![3D View](MCU%20Data%20Logger_3d_image.png)
