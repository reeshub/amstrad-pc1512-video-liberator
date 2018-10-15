# Bill Of Materials

Basic "bare bones" BOM for the Amstrad Video Liberator.

|Qty|Description|Notes|Resistor Colour Code|
|---|---|---|---|
|1|TI SN74LS04N Hex Inverter IC|(or equivalent)||
|5|75Ω 1/2W resistor<sup>1</sup>|for input pulldowns|violet/green/black|
|5|100Ω resistor|for inverter inputs|brown/red/brown|
|2|1.2KΩ resistor|for "pull both" intensity and black inputs|brown/red/red|
|3|1KΩ resistor|for RGB video outputs|brown/black/red|
|6|diode|||
|1|2 pin power connector|DuPont type, e.g. to go to pin header on motherboard<sup>2</sup>.||
|1|VGA 15-pin female connector|||

<sup>1</sup> Note the 1/2W pulldown resistor. Amstrad's original design actually used 1/4W, but bigger is always better for heat dissipation, and these can kick out some heat!
<sup>2</sup> Of course how you power this board is up to you, but I found it easiest to just use one of the pin headers on the motherboard for the +5V and GND. Check with a multimeter first!
