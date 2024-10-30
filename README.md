# Ai-HDL-MacroPad
Application Specific RP2040 based Keyboard for the PRISM Lab at the University of Arizona

Below are 3D renders and schematics 

![V1 0 PRISM Macro Pad_Front](https://github.com/user-attachments/assets/f874fd51-9041-4ddb-8332-def148d5e871)


![V1 0 PRISM Macro Pad_Rear](https://github.com/user-attachments/assets/7357fe59-80f8-425b-adbd-b3dc21ae9051)


![V1 0 Schematic](https://github.com/user-attachments/assets/f58809fa-fde0-4ae0-97ad-ebc165ffb292)


# TO DO

~~1. Create/Determine software~~ DONE

2. Determine Key Caps
3. Create a 3D model case (Clear plastic would be cool)
6. Link footprints, 3D renders, and symbols
7. Develop wifi version with battery + BT (maybe a screen? Extra version)
8. Remove board, move to on PCB IC instead of the board
9. Develop GUI for KMK
10.  Order and test


# Materials

| Item  | Quantity | Link |
| ------------- | ------------- | ---- |
| Seeed Studio XIAO RP2040  | 1  | [SeedStudio](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html)     |
| KTT Kang Ash Gray Tactile Switches  | 5  |  [KineticLabs](https://kineticlabs.com/switches/ktt/ktt-kang-ash-gray-switches)    |


# Firmware

This project will use the [KMK Firmware](https://github.com/KMKfw/kmk_firmware).
KMK has its own license, please refer to their page for more details.

# More Info

KTT switches can be replaced with any CherryMX-like switches. The XIAO RP2040 was used for accessibility (it doesn't require soldering an IC onto a board). KiCad files can be found in its folder. Production files can be found in Export Files. The hardware is designed to be used with CircuitPython for ease of use, but theoretically, the RP2040 can be flashed with QMK.
