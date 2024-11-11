# Ai-HDL-MacroPad
Application Specific nRF52840 based Keyboard for the PRISM Lab at the University of Arizona

Below are 3D renders and schematics 

## **Version 1**
![V1 0 PRISM Macro Pad_Front](https://github.com/user-attachments/assets/f874fd51-9041-4ddb-8332-def148d5e871)


![V1 0 PRISM Macro Pad_Rear](https://github.com/user-attachments/assets/7357fe59-80f8-425b-adbd-b3dc21ae9051)


![V1 0 Schematic](https://github.com/user-attachments/assets/f58809fa-fde0-4ae0-97ad-ebc165ffb292)

## **Version 1.5**

![V1 5 MacroPad Front](https://github.com/user-attachments/assets/ca0ab8e7-101f-47dc-ba49-5738d19202a8)

![V1 5 MacroPad Rear](https://github.com/user-attachments/assets/a3d8470d-8df4-4d5f-9a52-2fec045cd8ec)

![V1 5 MacroPad PCB](https://github.com/user-attachments/assets/d8d3c3e0-46ed-4039-af1c-5b4f5980b7ad)

![V1 5 Schematic](https://github.com/user-attachments/assets/f247798a-bfb1-4014-aebb-349ee96dda97)



# TO DO

1. Write software using KMK firmware

~~2. Determine Key Caps~~ DONE

3. Modify this 3D model for our needs (Coming soon)
6. Link footprints, 3D renders, and symbols
7. Develop wifi version with battery + BT 
9. Incorporate [POG](https://github.com/JanLunge/pog)
10.  PROTOTYPE!


# Materials

| Item  | Quantity | Link |
| ------------- | ------------- | ---- |
| Seeed Studio XIAO RP2040  | 1  | [SeedStudio](https://www.seeedstudio.com/XIAO-RP2040-v1-0-p-5026.html)     |
| KTT Kang Ash Gray Tactile Switches  | 5  |  [KineticLabs](https://kineticlabs.com/switches/ktt/ktt-kang-ash-gray-switches)    |


# Firmware

This project will use the [KMK Firmware](https://github.com/KMKfw/kmk_firmware).
KMK has its own license, please refer to their page for more details. KMK has a GUI interface that another developer made.

This [battery management](https://github.com/Tjoms99/xiao_sense_nrf52840_battery_lib) software will be used to communicate battery life and charge status to the user.

# More Info

KiCad files can be found in its folder. Production files can be found in Export Files. Version 1 is a super simple 5-key design for use with a XIAO RP2040. It does not have Bluetooth. It's also much cheaper. 
Version 1.5 has BT and a lithium-ion battery and relies on the KMK firmware.

This project is a team effort within the PRISM lab at the University of Arizona.
