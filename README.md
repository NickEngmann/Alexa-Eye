# Alexa Eye

Click the image below to watch the video.

[![Watch the video](https://github.com/NickEngmann/Alexa-Eye/blob/master/imgs/youtube.png)](https://www.youtube.com/watch?v=4e5KVpLYs1s)

This project is an extension of the 'Uncanny eyes' project by @Adafruit. 

Part List:

* 1.44" TFT LCD (#2088).  
* PJRC Teensy 3.1/3.2  OR Adafruit M0 and M4 boards (Feather, Metro, etc.).
* 3.5mm Stero Female Headphone Jack
* 6"-12" Auxilary Cable
* (OPTIONAL) Auxilary Cable Splitter

Check out Thingiverse for the 3D Printable files:
https://www.thingiverse.com/thing:3239394

Example Video:
https://www.youtube.com/watch?v=4e5KVpLYs1s

Build Instructions:
https://www.hackster.io/nick-engmann/alexa-eye-giving-an-echo-dot-some-personality-38705e


*** NOTES ***
This code uses features specific to these boards and WILL NOT work on normal Arduino or other boards!

How-to guide for the original Uncanny-eyes project with parts list is located here:
https://learn.adafruit.com/animated-electronic-eyes-using-teensy-3-1/overview


Teensy 3.x: use 72 MHz board speed -- 96 MHz requires throttling back SPI bitrate and actually runs slower!

Directory 'software' contains Arduino sketch for PJRC Teensy 3.1 & Adafruit M0 & M4. 'graphics' subfolder has various eye designs, as #include-able header files.