#STM32F4 development board#

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

Available as a shared project on [OSHPark](https://oshpark.com/profiles/MonkeyKungFu)

##Note regarding part population##

For STM32F405 parts, Populate C1 and C3 with 2.2uF capacitors.  Do not populate C5, R9.
For STM32F41x, STM32F4x1 parts, Populate R9 and C1 with 0 ohm Resistor.  Populate C5 with 4.7uF capacitor.  Do not populate C3.

##License##

This work is licensed under [CC Attribution 3.0 United States](https://creativecommons.org/licenses/by/3.0/us/).

