# ATmega328Pins.h

The header file in this repository provides definitions like `PIN_PB0` so you can use those names instead of Arduino pin numbers in your code.

I design my own PCBs sometimes, and find myself using the Arduino core often given that there are so many libraries available for that ecosystem.  When designing your own PCB, though, the hardware pin names (like "PB0", "PB1", ... "PE3") are much more salient than the Arduino pin numbers, and working with libraries that are expecting Arduino pin numbers can be tricky given that you'll have to look up the pin number that Arduino would use for a particuilar hardware pin name.

This header file solves that problem by doing that mapping for you.
