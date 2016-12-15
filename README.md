Library to operate HTU21D(F) Temperature and Humidity I2C sensor on Particle devices.

I just added a getError() function that propagates the error code from the I2C/ Wire functions to help troubleshoot a communication problem with the sensor.

Original source: https://github.com/romainmp/HTU21D

Tested on Particle Photon + Adafruit HTU21DF breakout board.
