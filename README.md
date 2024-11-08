# ML1RE
 Magic Leap 1 Reverse engineering and frankensteining efforts
## Contents
### PCB files
These are PCBs being used to analyze the different components of the Magic Leap 1, focusing on the Lightwear.
- A breakout board for DF40C-34D* mezzanine connectors, set up as a passthough (DP and DS on opposite sides). These are the connectors on the Lightwear's end of the ML1 cable.
- A breakout board for the DF40C-50D* mezzanine connectors, the second in a trilogy of similar boards. This is presumed to be the connector by which the LCOS display interfaces with the rest of the Lightwear. I have not yet confirmed this to be the correct connector. 
- A breakout board for the DF40C-20D* series mezzanine connectors, again in the same style. This is presumed to be the connector by which the LED module is powered and controlled by the rest of the Lightwear. I have not yet confirmed this to be the correct connector. 
- A replacement LED PCB, fitting within the footprint of the last. I've ordered it on a single sided aluminium board with through-hole headers. The LEDs have integrated focusing lenses, as opposed to seperate collimaters on the original. The LEDs are the HSMQ-C380 and HSMC-C380 from Broadcom, as well as the 150060BS84000 from Wurth. The LED also has through holes drilled in place of one red and one green LED. I've gotten it in my head that I can mount both a red and green laser behind the PCB. These will be the GH15130C8C (green) and the GH06510F4A (or any to33 red laser).
