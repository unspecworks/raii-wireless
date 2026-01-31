# Build Guide & Bill of Materials

## Bill of Materials (BOM)

*   **Microcontroller**: Nice!Nano v2 (2 qty)
*   **Switches**:
    *   Reset Tact Switch: B3U-1000P (2 qty)
    *   Power Switch: MK-12C02 (2 qty)
*   **Sockets**: Kailh Choc Hotswap Sockets (34 qty)
*   **Keys**:
    *   Kailh Choc v1 or v2 Switches (34 qty)
    *   Keycaps (34 qty) - *Note: Please ensure keycaps are compatible with Choc spacing.*
*   **Battery**: 3.7V LiPo Battery (2 qty)
    *   *Recommended sizes:*
        *   **301230**: For installation directly beneath the Nice!Nano MCU.
        *   **351636**: For use with the case.
*   **(Optional) Battery Connector**: PH2.0 or compatible connector (2 qty)
*   **(Optional - for Case)**: M2x6 Screws (8 qty)
*   **Feet**: Rubber feet or anti-slip pads

---

## Assembly Instructions

This keyboard supports two build configurations: **With Case** and **Without Case**. Please follow the instructions relevant to your chosen configuration.

### Option 1: Building With a Case

1.  **MCU Installation**:
    *   Solder the Nice!Nano MCU directly to the bottom side (the side with hotswap sockets) *without* pin headers.
    *   **Orientation**: The MCU components must face **outwards** (away from the PCB).
    *   **Insulation**: Since the MCU is soldered directly to the PCB, you **must** insulate the underside of the MCU (e.g., using Kapton tape) to prevent potential short circuits. While typically safe, this is a necessary precaution.
    *   **Trimming**: Trim any protruding pins on both the front and back of the PCB to ensure a flush fit.

2.  **Power Switch**:
    *   Install the power switch on the side opposite to the MCU (the top/switch side).

3.  **Reset Switch**:
    *   Install the reset switch on the bottom side. The bottom case includes a leaf spring mechanism designed to actuate the reset switch from this position.

4.  **Battery Connection**:
    *   When using the case, finding a suitably sized connector may be difficult. Therefore, **direct soldering** of the battery cables is recommended.
    *   **Jumper Configuration**: Bridge the appropriate battery jumpers on the PCB (verifying the front/back indicators).
    *   **Connection**: Solder the battery cables to the designated pads on the bottom side (hotswap socket side).

5.  **Final Assembly**:
    *   Place the top case over the PCB.
    *   Install the switches through the case into the sockets.
    *   Attach the bottom case and secure the assembly using the M2x6 screws.
    *   Attach feet to the bottom of the case.

### Option 2: Building Without a Case

1.  **MCU Installation**:
    *   Solder the MCU to the top side (switch side) using pin headers.
    *   **Orientation**: The MCU components must face **inwards** (towards the PCB).
    *   **Suggestion**: Consider using hotswap headers for the MCU or taller headers to create sufficient clearance for a battery underneath.

2.  **Power Switch**:
    *   Solder the power switch to either the top or bottom side, depending on your preferred operational position and battery placement.

3.  **Reset Switch**:
    *   Solder the reset switch to either the top or bottom side, whichever offers easier access.

4.  **Battery Connection**:
    *   You may use a battery connector or solder the battery directly.
    *   **Polarity Warning**: If using a connector, strictly verify the polarity to avoid damage.
    *   **Jumper Configuration**: Bridge the appropriate battery jumpers on the PCB before connecting the battery.

5.  **Final Assembly**:
    *   Install switches (with or without a plate).
    *   Attach feet to the bottom of the PCB.

