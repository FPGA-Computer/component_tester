Component tester

based on design from svn://mikrocontroller.net/transistortester/
Github: https://github.com/svn2github/transistortester

I made a few changes to the hardware for my own use:

- A boost mode power supply for operating from 1 AA NiMH battery at about 45mA.
  
- 16x2 characters LCD module with backlight High/low setting

- Power On/Off switch

- I/O mapping is based on Markus's version with the following exceptions:

*  ATMega328 in TQFP with 2.5V reference at ADC6 and Battery voltage at ADC

*  PC3 - PC5 are unused and are available on connector JP2


Project page:

https://hw-by-design.blogspot.com/2018/07/component-tester.html

Firmware: The files are from svn://mikrocontroller.net/transistortester/  
I only make a few minor changes to match my hardware.  They are included 
here for completeiness and I am not maintaining them.

Licensing:

Schematic: (in Eagle CAD) Creative Commons 4.0 Attribution 4.0 International

PCB & Layout: Creative Commons 4.0 Attribution 4.0 International

See https://creativecommons.org/licenses/by/4.0/

