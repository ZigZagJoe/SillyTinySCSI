SillyTinySCSI - Smallest SCSI emulator out there!
Derived from and firmware compatible with ZuluSCSI Pico OSHW.

<img width="600px" src="images/1699335723821.jpeg" />
<img width="600px" src="images/1699230611893.jpeg" />

V1.0: No bugs, however it is a double-sided board.
V2.0: Design for manufacturability improvements

Case design has been validated in 0.25mm ABS on a monoprice mini. May require changes on other printers. Not yet tested.
Requires 4x M2 x 7mm (or greater) machine screws or suitable self tapping screws.
Supports everywhere is *required* when printing. Suggest line support in cura, ensure that the lines run along the length of the slots 

See here for more discussion and assembly note: https://68kmla.org/bb/index.php?threads/sillytinyscsi-smallest-scsi-emulator-zuluscsi-oshw.45830/

---------------------------
Orginal document.....
---------------------------

ZuluSCSI™ Pico Community Edition - Open Source Hardware
========================

This repository contains the KiCAD 7 schematic and PCB design files for the Pico-based ZuluSCSI™ SCSI to SD storage emulator, which is derived from the ZuluSCSI RP2040 board design. Firmware for ZuluSCSI is available at http://github.com/ZuluSCSI/ZuluSCSI-firmware.

This hardware design is licensed under the terms of the strongly reciprocal CERN OHL-S V2 license, which can be viewed in full at https://ohwr.org/cern_ohl_s_v2.txt and https://ohwr.org/cern_ohl_s_v2.pdf. 

ZuluSCSI™ is a registered trademark of Rabbit Hole Computing, and may not be used commercially without the express written consent of Rabbit Hole Computing. Individuals producing ZuluSCSI boards for personal use are hereby granted permission to use the ZuluSCSI trademark in a noncommercial capacity.

_Any_ use of the ZuluSCSI trademark in a **commercial** context requires prior written consent from Rabbit Hole Computing.

<img alt="ZuluSCSI Pico OSHW board Render (top)" width="600px" src="images/ZuluSCSI-Pico-OSHW-Rev2023c-render-top.png" />

Firmware for ZuluSCSI is licensed under the GNU GPL Version 3, and can be found at https://github.com/zuluscsi/ZuluSCSI-firmware

Generating fabrication files
----------------------------

The component part numbers are stored in KiCAD schematic.
Manufacturing files, including assembly BOM, can be generated using [KiKit](https://github.com/yaqwsx/KiKit).
