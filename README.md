# REPO NAME: EagleTemplate-new
## License: Creative Commons Attribution-NonCommercial-ShareAlike

The improved CMRI8-RJ45 adapter (with limiting resistor pads) AND an inverter

This version is aimed at CMRI users using common cathode signals and a logic true output.
It includes a 74HC540 octal latch inverter (but the latches are hardwared on) to source 
~ 8 mA @ 4V, which should be adequate for modern LEDs.  Other versions of 74xx540 will 
probably work as well as 74xx541 (non inverting) although I haven't tested them.

John Plocher did the original design based on a request from Jay Beckham, and later extended
it to support limiting resistors based on user requests.  Kris Puccinelli modified this 
design to include an octal inverter, but not on EAGLE.  This is an EAGLE version, designed
for panelization.
