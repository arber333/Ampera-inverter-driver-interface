# Ampera-inverter-driver-interface
This is a simple board to interface with Ampera inverter. It has driver pins and current sensor contacts. I also put aside one temp sensor. On the left side there is also isolated voltage sensing interface designed for Johannes Huebner inverter.

Ver 2.3 Board is a little larger and it incorporates both connectors which are used for driver and sensor board on Rev2 controler. I recommend this board if you decide to go that route.
Additionally i included the inverter chip connected to BOTH driver connectors sou you can drive both IGBT bridges if you want to experiment. 

In the actual built I used Microchip MCP6001RT opamp variant which is inverted sensing. I think OPA344 is not a correct opamp.
I think you may have a problem in voltage polarity if you use another positive sensing opamp.
Also to clarify for isolated op amp i use Si8920 which is marked on board but model is ATTINY. It is just a mistake in using a wrong model for a chip.
To supply isolated voltage i use Murata NME0505SC which can withstand short on opamp indefinitely.
I am sorry if i caused confusion. I have just used the drawing for so long i forgot about some points.
