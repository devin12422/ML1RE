# ML1RE
 Magic Leap 1 Reverse engineering and frankensteining efforts
## Repo Contents
### PCB Gerbers
These are the PCBs currently being used to analyze and debug different connectors and components of the Magic Leap 1. Current efforts are focusing on the headset itself, with the current goal of at least interfacing with the headset over DisplayPort and USB C. The gerbers are as follows
- A breakout board for the DF40C-34D*-0.4 series mezzanine connectors, with the plug (DP) and socket (DS) on either side. I have confirmed this to be the connector on the headset end of the cable.
- A breakout board for the DF40C-50D*-0.4 series mezzanine connectors in the same fashion as the last. I have not yet confirmed this to be the correct connector. This is presumed to be the connector by which the LCOS display interfaces with the rest of the Lightwear.
- A breakout board for the DF40C-20D*-0.4 series mezzanine connectors, again in the same style. I have not yet confirmed this to be the correct connector. This is presumed to be the connector by which the LED module is powered and controlled by the rest of the Lightwear.
- A replacement LED module, hopefully fitting within the footprint of the last. I've ordered it on a single sided aluminium board with through-hole headers (as opposed to a flexible board with the mezzanine connector). The LEDs on board have integrated focusing lenses. These are the HSMQ-C380 and HSMC-C380 from broadcom, as well as the 150060BS84000 from Wurth Standard. The LED also has through holes drilled in place of one of both the red and green LEDs. This is because I've gotten it in my head that I can mount both a red and green laser behind the PCB. These lasers are the GH15130C8C (green) and the GH06510F4A (basically any to33 red laser).
