(Rabbit Mountain Research) AVR Arduino Pro Micro & Arduino Pro Mini ISP programmers
========================

This shield / carrier board, once assembled, turns your Arduino Nano, <S>Arduino Pro Mini, or Arduino Pro Micro</S> into an AVR ISP programmer. The ISCP socket is wired to work directly with the ArduinoISP code.

This board was designed to replace my old legacy TinyISP programmer from Adafruit (which no longer works easily with Ubuntu Linux). I would like a newer AVR ISP programmer that works without installing drivers AND has a more modern USB-micro or USB-C port. The Pro Mini version can be used with the new Sparkfun Serial Basic with USB-C (or any FTDI compatible Cable).

Currently I am having trouble getting the pro mini and pro micro versions to work. New tests on the protype pcbs are in progress. Might be a resistor problem or a grounding pin issue like the Nano version had.

<B>Update Nov-24-2021:</B> First Prtotype programmer using a USB-C Nano + Nano AVR ISP Programming Shield / Carrier Board was a success! Status LEDs, power jumper for target AVR, and everything seems to work. Was a minor error with the ISP pinout not being grounded, but fixing that fixed this version of the programmer. It also was able to reflash the arduino bootloader to an Arduino Mega 2560 (an old Rambo-Mini). My old Adafruit / Sparkfun TinyISP programmer was never able to program the 2560 AVR. Woo!!

Planning on putting together my first commercial run of PCBs for a small assembly of units for purchase. Please check Tindie / RabbitMountainResearch.com for more info on how to buy those if you are interested.

Repository Contents
-------------------
* **/Hardware** - All Eagle design files (.brd, .sch)
* **/Code** - Arduino *.Ino sketch file
