# SKR-3-EZ-Klipper-Compile-Settings

SKR 3 EZ has the wrong usb ports in their docs.

I screenshot my settings to help from all the pain I recieved just to get it too working.

ls /dev/serial/by-id
usb-Klipper_stm32h743xx_4C002B001651313238353730-if00 is my final results. 

make flash FLASH_DEVICE=0483:df11 when compiling .. make sure it in STMicroelectronics STM Device in DFU Mode by lsusb or sudo dfu-util -l

I used a pi 4 but plan to too ue in FLSUN V400 with FLSUN Speed pad.

good luck
