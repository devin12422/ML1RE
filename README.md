# ML1RE
 Magic Leap 1 hardware reverse engineering and renewal
## Contents
### Analysis PCBS
These are PCBs being used to analyze the different components & connectors of the Magic Leap 1, focusing on the Lightwear. I have elected to ignore this approach for the time being. I'm focusing on building new hardware instead of trying to reuse the old hardware.
- A breakout board for DF40C-34D* mezzanine connectors, set up as a passthough (DP and DS on opposite sides). These are the connectors on the Lightwear's end of the ML1 cable.
- A breakout board for the BM20B-50* mezzanine connectors. I have confirmed this to be the correct connector for the LCOS displays, though if memory serves, I could not buy connectors of the correct height.
- A breakout board for the DF40C-20D* series mezzanine connectors, again in the same style. This is presumed to be the connector by which the LED module is powered and controlled by the rest of the Lightwear. I have not confirmed this to be the correct connector. 


### Replacement PCBS
- A replacement LED PCB. Single sided aluminium PCB, wires or FPC needs to be soldered to front. The LEDs have integrated lenses, as opposed to the discrete collimators on the original. The leds are the HSM*-C320 series. Two boards stacked on top of eachother are required. There are no affordances for optical alignment as of yet.
	- All of the grounds for the LEDs are connected, though you could flip them and have their sources connected.
- A PCB to convert displayport into 2 sets of MIPI DSI for use with the Magic Leap's LCOS displays. The main chip on board is the TC358860XBG. You may have to buy it from aliexpress.
