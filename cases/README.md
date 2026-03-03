# RAII Wireless Cases

This directory contains the 3D design files (STEP format) for the RAII Wireless keyboard cases.

## Overview

The RAII Wireless case is a two-part (Top and Bottom) case designed to house the PCB, battery, and switches securely.

## Case Files

Files are provided in STEP format, which is compatible with most 3D CAD software and slicers.

### Left Half
- `RAII_W_L_TOP.step`: Top plate/shell for the left side.
- `RAII_W_L_BOT.step`: Bottom shell for the left side.

### Right Half
- `RAII_W_R_TOP.step`: Top plate/shell for the right side.
- `RAII_W_R_TOP_LOGO.step`: Top plate/shell for the right side with logo on the top.
- `RAII_W_R_BOT.step`: Bottom shell for the right side.

## Hardware Requirements

To assemble the case, you will need:

- **Screws**: M2x6mm screws (8 total, 4 per side).
- **Feet**: Rubber feet or anti-slip pads for the bottom case.

## Design Features

- **Reset Mechanism**: The bottom case includes a built-in leaf spring mechanism to actuate the reset switch without needing to open the case.
- **Battery Compartment**: Designed to accommodate a 3.7V LiPo battery (recommended size: 351636 for case builds).
- **Slim Fit**: Optimized for a low-profile aesthetic that protects the MCU and battery while keeping the switches and keycaps exposed.

## Printing Recommendations

- **Material**: PLA, PETG
- **Orientation**: Print with the flat faces on the bed.
- **Supports**: May be required depending on your printer's bridging capabilities, especially for the screw holes and internal cavities.

> [!WARNING]
> This case is designed for FDM printing. Other methods, such as resin printing, may not be suitable for this design.