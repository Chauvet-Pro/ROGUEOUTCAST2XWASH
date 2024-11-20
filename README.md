# Rogue Outcast 2X Wash

## Software Versions

[V1.240318 - Rogue Outcast 2X Wash](https://github.com/Chauvet-Pro/ROGUEOUTCAST2XWASH/blob/8e31a0135239faa3a1c7cfc9fa712da1aad084d3/firmware/V1.240318.zip)
- Fixed the issue wherein color swapping to white causes white to have a noticeable shift as it settles

[V1.230928 - Rogue Outcast 2X Wash](https://github.com/Chauvet-Pro/ROGUEOUTCAST2XWASH/blob/8e31a0135239faa3a1c7cfc9fa712da1aad084d3/firmware/A4078F-OUTCAST2XWASH-V1.230928.zip)
- Fixed the issue of ring flicker at low-end dimming

[V1.230504 - Rogue Outcast 2X Wash](https://github.com/Chauvet-Pro/ROGUEOUTCAST2XWASH/blob/8e31a0135239faa3a1c7cfc9fa712da1aad084d3/firmware/A4078F-OUTCAST2XWASH-V1.230504.zip)
- Added 55CH and 23CH personalities

[V1.221115 - Rogue Outcast 2X Wash](https://github.com/Chauvet-Pro/ROGUEOUTCAST2XWASH/blob/8e31a0135239faa3a1c7cfc9fa712da1aad084d3/firmware/V1_11-15-2022_A4078F-RogueOutcast2XWash.zip)
- Fixed minor USB-related bug

[V1.220606 - Rogue Outcast 2X Wash](https://github.com/Chauvet-Pro/ROGUEOUTCAST2XWASH/blob/8e31a0135239faa3a1c7cfc9fa712da1aad084d3/firmware/V1_06-06-2022_A4078F-RogueOutcast2XWash.zip)
- Released software version

&nbsp;

## USB Software Update Instructions
1.  Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message “***USB Update***” will be displayed. Press **< YES >**.
3.	The next screen will show the software versions available for this fixture on the USB drive. For multiple versions of the software for the same fixture, use **< UP >** or **< DOWN >** to select the desired version. Press **< ENTER >**.
4.	The ***"USB Update*** screen will re-appear. Press **< YES >**.
5.	The upgrade will start. DO NOT turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: ***"USB Update Wait"***. USB update can take several minutes to complete.
    > When the USB stops blinking, all the motors will power down, and the display will go blank. DO NOT turn off the power. The fixture will automatically reboot when the update is done.
6.  Go to **Sys Info** on the fixture's menu map and confirm the firmware revision.
7.	When the boot-up process is finished, restart the fixture.


### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the **UPLOAD 08** device to fix this. 
