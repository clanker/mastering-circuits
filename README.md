# mastering-circuits
Summaries, LTspice simulations, and lab results to follow The Encyclopedia of Electronic Circuits, Volume 1

## September 14, 2023

The replacement battery from my 2008 Macbook has died. Strange because I was using it five months ago. I must have not shut it down properly. I tried a battery charging circuit "Simple Ni-Cad Battery Charger" from p.112 but wasn't successful. The diode passed 11 mA current--mainly from the resistor--while only 0.6 mA went to the battery. I calculated that the battery would need 5000 hours to charge fully at such a low current. The circuit performed well, the 2000-ohm pot worked nicely in changing the voltage that appears at the battery terminals. The spice simulation is found in 11-battery-chargers/simple-nicad and shows how the cap-diode pair maintains a DC voltage from the 20 VAC input I used.


