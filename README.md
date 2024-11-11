# Ai-HDL-MacroPad
Application Specific nRF52840 based Keyboard for the PRISM Lab at the University of Arizona

Below are 3D renders and schematics 

## **Version 1.5**

![V1 5 MacroPad Front](https://github.com/user-attachments/assets/74f60da3-1517-4a8a-8ceb-e1e1f64ffbd6)

![V1 5 MacroPad Rear](https://github.com/user-attachments/assets/8f847f6d-fa53-45a6-b2bf-48b260a90974)


![V1 5 MacroPad PCB](https://github.com/user-attachments/assets/81ba3f00-b3bb-43f3-b944-0d1d49ffd889)

![V1 5 Schematic](https://github.com/user-attachments/assets/69e37617-77e7-41ba-a750-55ec24ab9309)

## Old Versions
**Version 1**
![V1 0 PRISM Macro Pad_Front](https://github.com/user-attachments/assets/f874fd51-9041-4ddb-8332-def148d5e871)


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
| seeed studio XIAO nRF52840  | 1  | [Mouser](https://www.mouser.com/ProductDetail/Seeed-Studio/102010448?qs=Znm5pLBrcAJ5g%252BWAkitg4w%3D%3D)     |
| Cherry MX Switches  | 6  |  [Mouser](https://www.mouser.com/ProductDetail/CHERRY/MX1A-C1NW?qs=sGAEpiMZZMtFyPk3yBMYYJ6eFtqPPgccKDEfiw%252Brqds%3D)    |
| Lithium-Ion Battery | 1 | [Option 1](https://www.digikey.com/en/products/detail/sparkfun-electronics/PRT-13851/6605199) [Option 2](https://www.digikey.com/en/products/detail/adafruit-industries-llc/258/5054544) |
| Battery connector | 1 | [Mouser](https://www.digikey.com/en/products/detail/jst-sales-america-inc/S2B-PH-K-S/926626) |
| Battery LED | 1 | [Mouser](https://www.digikey.com/en/products/detail/sparkfun-electronics/COM-16347/11630204)


# Firmware

This project will use the [KMK Firmware](https://github.com/KMKfw/kmk_firmware).
KMK has its own license, please refer to their page for more details. KMK has a GUI interface that another developer made.

This [battery management](https://github.com/Tjoms99/xiao_sense_nrf52840_battery_lib) software will be used to communicate battery life and charge status to the user.

# More Info

KiCad files can be found in its folder. Production files can be found in Export Files. Version 1 is a super simple 5-key design for use with a XIAO RP2040. It does not have Bluetooth. It's also much cheaper. 
Version 1.5 has BT and a lithium-ion battery and relies on the KMK firmware.

The screw size is M2 2.2mm.

Working on a version with the microcontroller directly on the board.

This project is a team effort within the PRISM lab at the University of Arizona.
