# dtmfdecoder
control software for hardware DTMF decoder module for the ICS Control PiRepeater products

This software works with a simple, inexpensive (~$5.00) MT8870 DTMF Decoder Module.   Even though the module specifies it runs at 5vdc, it actually operates just fine using 3.3v parasitic power from the GPIO pins on the PiRepeater controller.

The interrupt driven version has been merged into the master branch now that interrupts are functioning correctly.  
The old polling version has been moved to the polling branch

Be sure to fully read the comments in the dtmfdecoder.py file, as there are some changes that must be made to /boot/config.txt in order for the interrupts to work correctly.
