Connector J1
============

Right Column
* 1: 3.3V out, used for onboard SX1276 module, buy could also be used to power MCU.
* 3: Raw panel input, not used for anything on board *except* panel sense.
* 5: Raw panel input, could be used for charge controller IN+.
* 7: 4-6V supply in, could be taken from charge controller OUT+.
* 9: Panel sense out, could be sent to ADC for monitoring.
* 11: 4-6V supply sense out, could bne sent to ADC for monitoring.
* 13: GND (i.e. panel ground)
* 15: GND (i.e. charge controller OUT-)

Left Column
* 2: Radio interrupt out
* 4: Radio reset in
* 6: Radio SPI CS in
* 8: Radio SPI SCK in 
* 10: Radio SPI MOSI in
* 12: Radio SPI MISO out 
* 14: GND
* 16: GND
