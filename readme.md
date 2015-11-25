#STM32-breakout#
========
ARMKit2 Breakout and development board for the 64-pin LQFP STM32F405 microcontroller.

The STM32F405 is a 32-bit ARM Cortex M4 micro manufactured by ST Microelectronics.

This PCB breaks out all the GPIO pins in two 2x16 pin 0.1" headers.  Power is provided by a USB mini-B connector through a 3.3v LDO regulator.  The USB data pins are routed to the port A USB peripheral in order to enable use of ST's built-in bootloader.  A Boot-select button is provided to enable this. 

The design is intended to be as bare-bones as possible, while enabling access to most of the important chip features.  Other features of this design are:

* Reset button.
* Two LEDs on-board.
* Optional External HS Oscillator
* Optional External RTC Oscillator
* Standard 6-Pin programming header for ST/Link
* 3mm mounting holes

##License##

This work is licensed under [CC Attribution 3.0 United States](https://creativecommons.org/licenses/by/3.0/us/).

