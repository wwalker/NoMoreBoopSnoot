# PowerConsumption

Current prototyping is being done with a Raspberry Pi 4B.

Various documentation states that the RPi 4B consumes 500-1000 mA according to load (not counting current supplied to external devices).

In my prototyping, I am using a 20,000 mA hour USB backup power device.  At high efficiency, it should have lasted 20 to 40 hours, yet it only lasted about 7 hours.

Must consider moving to another platform.  These are possibilities:
* Raspberry Pi Zero
* Various Arduino Uno-ish devices
* Various ESP8266 devices
* Various  SAMD21 devices (usually arduino compatible)

Rough microcontroller power consumptions:

| Controller     | current draw  | Info                                                              |
| ---            | ---           | ---                                                               |
| RPi 4          | 400 to 900 mA | Easy, but a power pig                                             |
| RPi Zero W     | 300 mA        | Still easy less power                                             |
| RPi Zero       | 100 mA        | Still easy, no wifi, program changes more involved                |
| seeeduino Xaio | 20 mA         | Medium hard, very limited memory, CPU speed, USB programming only |
