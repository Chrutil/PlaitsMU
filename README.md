# PlaitsMU
The Plaits Macro Oscillator ported to MU

This project is the Plaits Macro Oscillator by Mutable Instruments ported to MU large format modular.

The size of the PCB has been increased and the layout expanded for a 2MU module.
The footprint of most components have been changed to a larger 0805 size, for an easier build.
A few components were left at 0603 size since I could not find a suitable replacement.
The Power connector is a Synthesizers.com standard using -15v/+15v.
There are 12v power regulators added to feed the module the +/-12v it expects.
There is also a footprint for a MOTM power connector, but it is untested. 
I also suspect the io PCB is too wide for a double wide MOTM panel, but I have only tested MU so you are on your own there.

The best way is to select components is to look at the original BOM and pick the appropriate components with the expanded footprint.
I did this and will post my parts selection in the coming days, with no guarantees that I got it correct.

The STM32 mcu is the same as the original module and a very fine pitched IC with 0.5mm pitch so that will be the most challenging part.
I suggest starting with that one to make sure you got that right before populating the rest of the board.

