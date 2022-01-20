# PowerConsumption

Current prototyping is being done with a Raspberry Pi 4B.

Various documentation states that the RPi 4B consumes 500-1000 mA according to load (not counting current supplied to external devices).

In my prototyping, I am using a 20,000 mA hour USB backup power device.  At high efficiency, it should have lasted 20 to 40 hours, yet it only lasted about 7 hours.

Must consider moving to another platform.  These are possibilities:
* Raspberry Pi Zero
* Various Arduino Uno-ish devices
* Various ESP8266 devices
* Various  SAMD21 devices (usually arduino compatible)
