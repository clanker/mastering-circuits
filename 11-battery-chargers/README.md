# 11-Battery Chargers

## Simple Ni-Cad Battery Charger, p.112 (simple-nicad)

The replacement battery from my 2008 Macbook has died so I tried this simple battery charging circuit. Unfortunately the Macbook battery won't allow direct charging so this experiment wasn't successful. 

I measured that the diode passed 11 mA current--mainly from the resistor--while only 0.6 mA went to the battery. I calculated that the battery would need 5000 hours to charge fully at such a low current. The circuit performed well, the 2000-ohm pot worked nicely in changing the voltage that appears at the battery terminals. 

The spice simulation shown in simple-nicad (inverted from the book's schematic) shows my measured values for the cap and pot. I used generic diode and pnp devices that were sure to handle a large  current (that never materialized unfortunately). The png shows a transient analysis that was pretty accurate to the lab test.

First power experiment and I didn't get electricuted. :)


