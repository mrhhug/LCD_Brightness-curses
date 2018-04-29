# LCD_Brightness-curses
A curses program that adjusts a screen's backlight 

## Quick Start guide
clone, compile, run
<pre>gcc -Wall ./LCDbrightness.c -lncurses -o LCDbrightness.out && ./LCDbrightness.out</pre>

## Tested on
Archlinux

Manufacturer: ASUSTeK Computer Inc.

Product Name: K60IJ

## Adjustments for your system
You may have to adjust /sys/class/backlight/intel_backlight/max_brightness to match your system


## Screenshot
![Screenshot](https://raw.githubusercontent.com/mrhhug/LCD_Brightness-curses/master/Screenshot.png)
