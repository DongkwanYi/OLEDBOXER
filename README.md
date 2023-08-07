Hi,

This repository is for 2.42" OLED mod of Radiomaster BOXER transmitter.

Based on EdgeTX v2.8.4, code for OLED is developed.

"lcd_driver_spi.cpp" on main, copy&paste to your gitpod IDE, compile it.

* file location : EdgeTX/edgetx/blob/v2.8.4/radio/src/targets/taranis/lcd_driver_spi.cpp

* Gitpod for compile : https://github.com/EdgeTX/edgetx/wiki/Building-radio-firmware-in-a-webbrowser-with-Gitpod

* Or, download "OLEDBOXER28x_mode1.bin" or "OLEDBOXER28x_mode2.bin" and flash it!(choose your default stick mode, don't forget bootloader flashing!)

Wiring and hardware photos are attached. OLED is 2.42" 128*64 SPI interface. you can search "2.42 OLED", like diymore product.

This code may apply X7 family TX, like BOXER, ZORRO, TX12 and POCKET(maybe).

Enjoy flying!

/******************************************************************

The code for OLED is developed by Guru engineer,

Brain(Y.S.Cho)

Thank you!!!

/******************************************************************

Changes on "lcd_driver_spi.cpp" : 

SPI mode(mode 3 -> mode 0), SPI clock(fpclk/8) and a whole OLED initialize code are modified.
