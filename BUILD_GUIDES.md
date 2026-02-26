# Build Guide & Bill of Materials

## Bill of Materials (BOM)

| Item | Specification | Quantity | Notes |
| :--- | :--- | :--- | :--- |
| **Microcontroller** | Nice!Nano v2 | 2 | Pro Micro compatible |
| **Switches** | Kailh Choc v1 or v2 | 34 | |
| **Hotswap Sockets** | Kailh Choc Hotswap | 34 | |
| **Keycaps** | Choc Compatible | 34 | Ensure Choc spacing compatibility |
| **Reset Switch** | B3U-1000P | 2 | Tactile switch |
| **Power Switch** | MK-12C02 | 2 | Slide switch |
| **Battery** | 3.7V LiPo | 2 | 301230 (under MCU) or 351636 (with case) |
| **Screws** | M2x6mm | 8 | Required for case build |
| **Feet** | Rubber pads | - | Anti-slip |
| **Battery Connector**| PH2.0 (Optional) | 2 | Direct soldering recommended for cases |

---

## Assembly Instructions

Choose one of the two build configurations below based on whether you are using a case.

### Option A: With Case

![raii-wireless-case](./images/raiiww-2.webp)

This method involves soldering the MCU directly to the PCB to achieve the slimmest possible profile.

1.  **MCU Installation**
    *   **Side**: Solder to the **bottom** (socket side).
    *   **Orientation**: Components must face **outwards**.
    *   **Safety**: Insulate the MCU underside (e.g., with Kapton tape) and trim all pins flush to prevent shorts.
2.  **Switches**
    *   **Power**: Install on the **top** (switch side).
    *   **Reset**: Install on the **bottom** (the case features a leaf spring to actuate this switch).
3.  **Battery**
    *   **Connection**: Direct soldering is recommended.
    *   **Jumpers**: Bridge the battery jumpers on the PCB before connecting.
4.  **Final Steps**
    *   Place the top case, install switches through the case, attach the bottom case, and secure with M2x6 screws.

---

### Option B: Without Case (Standard Build)

![raii-wireless-case](./images/raiiww-5.webp)

A more traditional build using pin headers for the MCU.

1.  **MCU Installation**
    *   **Side**: Solder to the **top** (switch side) using pin headers.
    *   **Orientation**: Components face **inwards** (towards the PCB).
    *   **Tip**: Use sockets or tall headers if you plan to tuck the battery underneath.
2.  **Switches**
    *   **Power/Reset**: Can be installed on either side depending on preference.
3.  **Battery**
    *   **Connection**: Use PH2.0 connectors or direct solder.
    *   **Jumpers**: Bridge the battery jumpers on the PCB first.
4.  **Final Steps**
    *   Install switches into hotswap sockets and attach rubber feet directly to the PCB.
