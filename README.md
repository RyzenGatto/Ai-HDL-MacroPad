# Ai-HDL-MacroPad
Application Specific nRF52840 OR RP2040 based Keyboards for the PRISM Lab at the University of Arizona

Below are 3D renders. Schematic for the latest version is available in the Repo.

NOTE: If you want to adapt this to your own project with more keys, get familiar with KiCad and learn keyboard matrices (KMK has a good guide in their repo). 

## Info

KiCad files can be found in its folder. Production files can be found in Export Files. Version 1 is a super simple 5-key design for use with a XIAO RP2040. It does not have Bluetooth. It's also much cheaper. 
Version 1.5 has BT and a lithium-ion battery and relies on the KMK firmware.

## Version 2.4 
Fully integrated Macro Design. This design has been optimized for long-term reliability and has been simplified. 


![image](https://github.com/user-attachments/assets/1a8a2b9d-948f-49f5-b890-152c39657a80)

![image](https://github.com/user-attachments/assets/e13b1af5-5f3b-42fd-9767-627fe8d97e1c)



## Old Versions
**Version 1**
This is the cheapest version. It can be assembled by hand, no BOM or pick and place needed.
![V1 0 PRISM Macro Pad_Front](https://github.com/user-attachments/assets/f874fd51-9041-4ddb-8332-def148d5e871)

**Version 1.5**
Basically V1 but with BLE and a battery and M2 2.2mm screws.
![V1 5 MacroPad Front](https://github.com/user-attachments/assets/74f60da3-1517-4a8a-8ceb-e1e1f64ffbd6)

![V1 5 MacroPad Rear](https://github.com/user-attachments/assets/8f847f6d-fa53-45a6-b2bf-48b260a90974)

![V1 5 Schematic](https://github.com/user-attachments/assets/69e37617-77e7-41ba-a750-55ec24ab9309)

**Version 2.3 (Test PCB)**
![2 xx Front](https://github.com/user-attachments/assets/a0379b9e-45d4-494c-a37f-6cfbc64858e7)

![2 xx back](https://github.com/user-attachments/assets/d9661f9c-5e69-4506-962d-fb985575b9a9)

# TO DO

1. Write software using KMK firmware

~~2. Determine Key Caps~~ DONE

~~3. Develop wifi version with battery + BT~~ DONE

4.  PROTOTYPE!


# Materials
ONLY FOR V1.5
| Item  | Quantity | Link |
| ------------- | ------------- | ---- |
| seeed studio XIAO nRF52840  | 1  | [Mouser](https://www.mouser.com/ProductDetail/Seeed-Studio/102010448?qs=Znm5pLBrcAJ5g%252BWAkitg4w%3D%3D)     |
| Cherry MX Switches  | 6  |  [Mouser](https://www.mouser.com/ProductDetail/CHERRY/MX1A-C1NW?qs=sGAEpiMZZMtFyPk3yBMYYJ6eFtqPPgccKDEfiw%252Brqds%3D)    |
| Lithium-Ion Battery | 1 | [Option 1](https://www.digikey.com/en/products/detail/sparkfun-electronics/PRT-13851/6605199) [Option 2](https://www.digikey.com/en/products/detail/adafruit-industries-llc/258/5054544) |
| Battery connector | 1 | [Mouser](https://www.digikey.com/en/products/detail/jst-sales-america-inc/S2B-PH-K-S/926626) |
| Battery LED | 1 | [Mouser](https://www.digikey.com/en/products/detail/sparkfun-electronics/COM-16347/11630204)

2.xx Materials are available in the BOM of the KiCad Files.

# Firmware

This project will use the [KMK Firmware](https://github.com/KMKfw/kmk_firmware).
KMK has its own license, please refer to their page for more details. KMK has a GUI interface that another developer made.

This [battery management](https://github.com/Tjoms99/xiao_sense_nrf52840_battery_lib) software will be used to communicate battery life and charge status to the user.




Software by [this guy](https://github.com/ernesto-martinez1)
