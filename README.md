This is the Readme for my Raspberry Pi-5 Hat to control Astrophotography equipment.

This repository comes with absolutely NO Warranty, and is currently "in work".  There are several improvements I need to make to this design, the first of which is redesigning to use a larger format 5V buck converter.  The current buck converter is very small and difficult to solder using home shop air soldering techniques.

There is also a wiring bug in the 1-wire connections.  If you are going to use 1-wire, please connect directly to your Rpi or you will burn up your device and possibly the Rpi's power supply.

The UART connection works successfully.  Use ttyAMA0 and enable "UART0" on your Rpi.

I am planning on doing a complete rework of this design, hopefully before the end of 2025.  Planned improvements:

    1. Rework the Anderson Power Poles so they are used as stock instead of needing to be bent.
    2. Rework the APPs so they have a much more solid mount to the hat
    3. Extend the hat so it extends to the edge of the ethernet socket - more real estate
    4. I have found a larger 5V buck regulator that is much easier to solder using home hot air techniques
    5. Figure out why 1-wire circuit burns up the devices . . 
    6. There is a wiring bug that is fixed in the schematic, but is not fixed on the board traces.  This bug requires a bodge wire be installed on the 5V regulator to make it stable.  This is also very difficult to install.

