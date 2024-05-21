# CH32V003-Dev-Board
<p float="left">
  <img src="https://github.com/Strat00s/CH32V003-Dev-Board/blob/5b81b4377a25a637bfdaf578a3d197af4e0a5249/img/front.png?raw=true" width="150" height="280">
  <img src="https://github.com/Strat00s/CH32V003-Dev-Board/blob/5b81b4377a25a637bfdaf578a3d197af4e0a5249/img/back.png?raw=true" width="150" height="280">
</p>

A minimal CH32V003F4U6 based dev board for playing with the CH32V003 MCU.

The board should have everything required to get the chip working, together with a ME6211C33M5 3v LDO. The LDO is not required and can be ommited, but LEDs won't work as they are powered from it. The 3V and 5V rails can be joined together to power them again. USB is wired to hopefully support [RV003USB](https://github.com/cnlohr/rv003usb) bootloader.
