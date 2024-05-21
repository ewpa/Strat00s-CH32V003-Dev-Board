# CH32V003-Dev-Board

A minimal CH32V003F4U6 based dev board for playing with the CH32V003 MCU.

The board should have everything required to get the chip working, together with a ME6211C33M5 3v LDO. The LDO is not required and can be ommited, but LEDs won't work as they are powered from it. The 3V and 5V rails can be joined together to power them again. USB is wired to hopefully support [RV003USB](https://github.com/cnlohr/rv003usb) bootloader.
