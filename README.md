![MuaKissGIF](https://github.com/user-attachments/assets/0028f6bf-6811-47a8-9848-f291ee0c1f7d)

😖😖OLED EdgeTX V2.11.3 are uploaded!😖😖
😖😖OLED EdgeTX V2.11.3 are uploaded!😖😖


helpful videos :

https://youtu.be/VSOvrYYSIN4

https://youtu.be/cFsVHiim-Eo

https://youtu.be/LZEmpTxd5Lc

Hi,

This repository is for 2.42" OLED mod of Radiomaster BOXER, TX12, TX12MK2, ZORRO, POCKET, MT12(Surface TX) And

Jumper T12MAX transmitter(BW screen radios).

On August 3 2023, based on EdgeTX v2.8.4, code for OLED was developed.

After EdgeTX V2.10.RC, The code for SSD1309 driver of OLED is included on the source, but not activated. So I built the mod firmwares using it.

After hardware mod, flash the firmware in firmwares folder. Please check OLEDBOXER/firmwares/README file!

ie) If you are Radiomaster BOXER user, download "OLEDBOXER210x.bin" and flash it!(don't forget bootloader flashing!)
    Check stick mode after flashing!

Wiring and hardware photos are attached. OLED is 2.42" 128*64 SPI interface, SSD1309 or compatible driver. you can search "2.42 OLED", like TZT OLED or diymore's.

I recommend TZT's 2.42" OLED. It is cheap and same quality with diymore's. Also has more thin PCB, it is good for mod.

Enjoy flying!

/******************************************************************

The code for OLED is developed by Guru engineer,

Brain(Y.S.Cho)

Thank you!!!

Changes on "lcd_driver_spi.cpp" : 

SPI mode(mode 3 -> mode 0), SPI clock(fpclk/8) and a whole OLED initialize code are modified.

/******************************************************************



-------------------------------------------------------------------
(Old Readme)
Hi,

This repository is for 2.42" OLED mod of Radiomaster BOXER, TX12, TX12MK2, ZORRO, POCKET, MT12(Surface TX) transmitter(BW screen radios).

Based on EdgeTX v2.8.4, code for OLED is developed.

This code can apply 128*64 BW X7 family TX, like BOXER, ZORRO, TX12 and POCKET.

"lcd_driver_spi.cpp" on main, copy&paste to your gitpod IDE, compile it.

* file location : EdgeTX/edgetx/blob/v2.8.4/radio/src/targets/taranis/lcd_driver_spi.cpp

* Gitpod for compile : https://github.com/EdgeTX/edgetx/wiki/Building-radio-firmware-in-a-webbrowser-with-Gitpod

* Or, download "OLEDBOXERxxx_mode1.bin" or "OLEDBOXERxxx_mode2.bin" and flash it!(choose your default stick mode, don't forget bootloader flashing!)

Wiring and hardware photos are attached. OLED is 2.42" 128*64 SPI interface. you can search "2.42 OLED", like TZT OLED or diymore product.

Enjoy flying!
