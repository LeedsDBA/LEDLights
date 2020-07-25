LED strip i'm using is WS2812B compatible - https://amzn.to/3303nyW
and uses 5050SMD LEDs - 5V DC, 350-450mcd/led - http://led-obzor.com/led/technical-specifications-smd-5050
Per LED:
 - Power: 0.21 W
 - Supply voltage: 3.3 volts
 - Rated current: 60mA (3x 20mA - per R/G/B)

 The strip we're working with is 36 pcs long, so:

 60mA * 36 pcs = 2160 mA = 2.16 A @ 3.3VDC - which is probably 3x LEDs too much for a 2A USB feed...
 60mA * 33 pcs = 1980 mA = 1.98 A @ 3.3VDC

 Arduino will need a supply, and the LEDs will need a supply