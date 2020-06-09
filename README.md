# C64-replacement-PSU-230VAC-
This is a replacement PSU for the Commodore C64. The original PSUs from the 1980s and early 1990s tend to die and damage the connected C64, so it is recommended to get a new power supply for the C64.
This design is straight forward: a transformer, bridge rectifier and DC/DC converter for the 5VDC and a separat winding for the 9VAC. Nothing fancy. It was paid attention to use parts which are easily available (in Germany). Everything, except the 4 conductor cable for the output voltage are sourced from reichelt.de.
A further goal was a decent documentation.

Find some info on the required cable making <a href="http://tech.guitarsite.de/cable_making.html">on my website</a>

<img src="https://github.com/svenpetersen1965/C64-replacement-PSU-230VAC-/blob/master/C64%20Replacement%20PSU%20(230V)/Rev.%202/pictures/1719_-_PSU_outside.JPG" width="300" alt="C64 replacement PSU (outside)">
      
<img src="https://github.com/svenpetersen1965/C64-replacement-PSU-230VAC-/blob/master/C64%20Replacement%20PSU%20(230V)/Rev.%202/pictures/1720_-_PSU_Inside.JPG" width="300" alt="C64 replacement PSU (inside)">

# three-way mains connector
The R/C combination (1MOhm/10nF) between GND and PE has a very positive effect: The capacitive mains couplings that usually happens in cheap SMPS, that are used for the S-Video/HDMI converters, the Pi1541 etc. is suppressed this way. No more flickering when touching the user port or cassette port. Thus, it is recommended to place those components and use a three-way appliance connector for mains.

# Calculation of the BOM prices
The BOM v2.0 was calculated. The total price of the components (case included) is 47.58€ (June 9th, 2020). 
