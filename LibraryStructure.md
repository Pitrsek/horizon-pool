## Capacitor Class

Contain components that are able to store energy in form of electric charge. 

### What belongs into this class:

- ​	Fixed capacitors
- ​	Variable capacitors
- ​	Safety capacitors

### Parameters:

- Capacitance [F]
- Voltage Rating [V]
  -  DC value, or recalculated from AC rating if DC is not aviable
- Tolerance [%]  
  - If positive 	and negative tolerances differs, use worse.
- ​	Dielectric Type  
  - ​		Describes dielectric type e.g. X7R, MKT, MKP, Y5V, C0G/NPO
- Safety Class  
  - E.g. X2, Y1, X1Y2
- ​	Resistance [Ohm]
  - ESR value from 	datasheet.  	
  - Dissipation 	factor cannot be used, because is is defined for low frequency 	(i.e. 120Hz).
- Height
- ROHS