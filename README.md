# Duinotech-LoRa-Shield-to-Duinotech-LoRa-Gateway
Connection between a Duinotech Uno Board/LoRa Shield AND Duinotech IoT LoRa Gateway/Hub.

So I'm very new to the whole Arduino/Duinotech MCU technology and associated programming as such.
However I have a very long history with digital electronics down to the component level when I was younger in the 80's when I was in the RAAF for 18 years
Since then I've branched off into Network Engineering and have been maintaining, fixing, designing, and building large scale Corporaste Enterprise IT Networks for 20 years.

I bought a 23 Acre property a few years back in South East Quessland, Australia (Gynpie), and have gone off grid in relation to mains power.
The property is roughly shaped like a large "battle axe", with lots of gullies, semi-dense trees and sparse vegetaion in between.
I've recently completed building a large 4 bay shed, with the vision of Solar Power, Batteries and inverters. The shed is up on the road frontage, 100Metres above Sea Level.
The rest of the property is behind the shed going down to the first gully at about 80-85 Metres above sea level. (A drop of about 15-20 Metres some 100 Metres behind the shed)
The remainder of the property (20 Accres) is undulating creek gullies at horizontal distances 300-450metres form the shed around the 70-80 Metres above Sea level. (below Shed)

I have a dam on the propert about 300 Metres from the shed in the middle of the property, and there are various locations where I plan to pump water to from the dam
One of those locations is back up to the Shed, and then up into a header tank elevated 5-10 Metres above the storage tank.
This means not only will I need to pump water 300M in 63mm (2-1/2 inch) pipe to a main 10,000 Litre Storage tank, but also up hill about 20Metres to the shed.
From the storage tank at the shed, I then plan to use a smaller pump to fill the header tank a further 5-10 Metres higher.
This will then allow be to irrigate the whole property wherever I want water using 25-30 Metres of static pressure without pumps, 24hrs a day (whilst water lasts)

This is where this project comes into play.....

Detecting water levels, Starting Pumps, turning shutoff valves on/off to redirect water,....etc.  This all needs to be automated, 
and across large distances 300-500 Metres without having to run wires.  I then need be able to control this manually from my normal abode some 100 Kilometres away 
in Buderim, using the Internet.

LoRa appears to be a good solution for low BW comms across these 300-500 metre distances on the property, and then be controllable through a gateway to the Internet.
I have a lot of 200W solar panels that can be set up at any location on the property with MPPT chargers and 100A/hr batteries to run pumps, and switch water direction as needed.
This local power can also run LoRa Remote stations at these locations to provide telemetry data and receive control signals from the main hub location up at the shed.

