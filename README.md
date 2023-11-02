
Current sensor circuit with over voltage protection.

The Voltage supported is 12<=V<=18 as this is the working range of the TL092 OpAmps used in this project.

The shunt is a 1ohm 10 watt resistor, so use current*voltage under 10watt

The overvoltage protection circuit makes sure the output is NEVER above the Vref set by 
the TL431 IC in the circuit, a potentiometer is connected for ease of setting it to 
whatever your microcontroller max Vdd (e.g 3.3v or 5v).

A single layer PCB is also designed if needed.
