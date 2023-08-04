Hi,

This repository is for 2.42" OLED mod for RM BOXER.

Based on EdgeTX v2.8.4, code for OLED is developed.

"lcd_driver_spi.cpp" on main, copy&paste to your gitpod IDE, compile it.

* file location : EdgeTX/edgetx/blob/v2.8.4/radio/src/targets/taranis/lcd_driver_spi.cpp

* Gitpod for compile : https://github.com/EdgeTX/edgetx/wiki/Building-radio-firmware-in-a-webbrowser-with-Gitpod

* Or, download "OLEDBOXER284.bin", and flash it!

Wiring and hardware photos are attached.

This code may apply X7 family TX, like BOXER, ZORRO, TX12 and POCKET(maybe).

Happy flying!

/******************************************************************

The code for OLED is developed by Guru engineer,

Brain(Y.S.Cho)

Thanks!!!

/******************************************************************

Changes on "lcd_driver_spi.cpp" : 

SPI mode(mode 3 -> mode 0), SPI clock(fpclk/8) and a whole OLED initialize code are modified.
