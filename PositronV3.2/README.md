# Positron V3.2

This directory contains information about PCBs used in the Positron V3.2.



The Positron system consists of three PCBs, a touch controller and the umbilical cables. 

- **LDO Positron Mainboard**, It is a motherboard specifically designed for PV3.2 kits. It features Raspberry Pi Arm Cortex-M0+ RP2040 MCU, with 4 TMC2209 stepper drivers and 3 fan ports. It also features an onboard USB hub which expands the RPI host connectivity with ethernet and an USB A port.
- **PV3 Toolhead PCB**, It is a toolboard PCB specifically designed for the PV3.2 kits. It features RP2040 MCU and ADXL345 accelerometer all integrated into one board.
- **PV3 Switch PCB**, It controls the printer switch and reduce the current thus preventing the switch from overheating.
- **Umbilical Cable**, It is a custom flex cable that is rated for drag chain use. It delivers 24V power to the toolhead PCB while also carrying USB data.
- **PV3 Touch Controller**,  It features a touch screen with a Raspberry Pi CM4.

## Features

- **Convenient wiring**, wire up the entire printer with a few simple cables.
- **USB Klipper connection**, no additional software or hardware setup.
- **Exposed Connectivity**, with a PCB form factor designed specifically for the Positron, USB and ethernet ports are directly exposed and allow for easy connections
