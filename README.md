# AS5601-Arduino
AS5601 Magnetic encoder & Arduino
Overview and basic programming in Arduino
Enkoder magneryczny AS5601 podstawy i proste programowanie
***********
This moment we are interested only in quadrature output. Default setting is 8 positions for one turn.
It can be changed via I2C by changing ABN mapping. Maximum value is 2048. Be zareful. If you want to compare as5601 with mechanical encoder you have to remember, that "mechanical tick" it's a 4 positions !!! 
Example:
If your Arduino encoder library count 1x (for example brianlow library used in "zlomek") you should program AS5601 to 4x positions as you want!!! 
If your Arduino encoder library count 4x (for example PJRC library with interrupts) you should program AS5601 to 1x positions as you want!!! 
