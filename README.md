# Ai-HDL-MacroPad
Application Specific nRF52840 OR RP2040 based Keyboards for the PRISM Lab at the University of Arizona

Below are 3D renders. Schematic for the latest version is available in the Repo.

## Version 2
Fully integrated Macro Design. This is the test PCB with a few GPIO pins connected to some headers + the RP2040 RUN pin

![image](https://github.com/user-attachments/assets/e7061f74-a7d0-455c-bbb5-b828c55c7cb8)


![image](https://github.com/user-attachments/assets/9c2a6119-990e-4c3f-8349-464e670b56a3)



## Old Versions
**Version 1**
This is the cheapest version. It can be assembled by hand, no BOM or pick and place needed.
![V1 0 PRISM Macro Pad_Front](https://github.com/user-attachments/assets/f874fd51-9041-4ddb-8332-def148d5e871)

**Version 1.5**
Basically V1 but with BLE and a battery and M2 2.2mm screws.
![V1 5 MacroPad Front](https://github.com/user-attachments/assets/74f60da3-1517-4a8a-8ceb-e1e1f64ffbd6)

![V1 5 MacroPad Rear](https://github.com/user-attachments/assets/8f847f6d-fa53-45a6-b2bf-48b260a90974)

![V1 5 Schematic](https://github.com/user-attachments/assets/69e37617-77e7-41ba-a750-55ec24ab9309)

# TO DO

1. Write software using KMK firmware

~~2. Determine Key Caps~~ DONE
3. Link footprints, 3D renders, and symbols
~~4. Develop wifi version with battery + BT~~ DONE
6.  PROTOTYPE!


# Materials
ONLY FOR V1.5
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




Software by [this guy](https://github.com/ernesto-martinez1)
