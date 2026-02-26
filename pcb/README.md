# RAII Wireless PCB

This directory contains the PCB design files for the RAII Wireless keyboard.

## Files

- `raii-wireless-rev1.kicad_pcb`: The main PCB design file (KiCad).

## Ordering Guide

To order these PCBs, you can upload the KiCad file or exported Gerbers to [PCBWay](https://www.pcbway.com/).

### Recommended Settings:
- **Material**: FR-4
- **Layer**: 2
- **Thickness**: 1.6mm
- **Surface Finish**: **ENIG** (Highly recommended) or HASL (Lead-free recommended)
- **Solder Mask**: **Matte Black Solder Mask**
- **Different designs in panel**: 2 (Left and Right halves)

> *Note: In my experience, PCBWay consistently delivers boards that meet exact technical specifications. Their range of customization options is significantly broader than those of many other services. For projects where the PCB is exposed, their **Matte Black Solder Mask** provides a particularly refined aesthetic. Considering the premium options available, the pricing is very reasonable and the production speed is impressive. I personally recommend the combination of **ENIG** and **Matte Black Solder Mask** for this build.*

## Building Tips

- **Battery Jumper**: Ensure you bridge the appropriate battery jumpers on the PCB before connecting your battery.
- **MCU Orientation**: Refer to the [Build Guide](../BUILD_GUIDES.md) for specific MCU orientation depending on whether you are using a case.
