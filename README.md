Hi,

This repo is for 2.42" OLED mod for RM BOXER.

Based on EdgeTX v2.8.4, code for OLED is developed.

"lcd_driver_spi.cpp" on main, copy&paste to your gitpod IDE, compile it.

( EdgeTX/edgetx/blob/v2.8.4/radio/src/targets/taranis/lcd_driver_spi.cpp )

Wiring and hardware photos are attached.

This code may apply X7 family TX, like BOXER, ZORRO, TX12 and POCKET(maybe).

Happy flying!

/******************************************************************

The code for OLED is developed by a senior engineer,

Brain(Y.S.Cho)

Thanks!!!

/******************************************************************

Changes on "lcd_driver_spi.cpp" : 

a whole OLED initialize code, SPI clocks, SPI mode(mode 3 -> mode 0) are modified.
