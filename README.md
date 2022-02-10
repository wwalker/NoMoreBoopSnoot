# NoMoreBoopSnoot

A hardware and software system to assist blind canines with obstacle avoidance

An ongoing project to make blind dogs (and likely other animals) more confidnent and safer by providing Obstacle Avoidance warnings to the dog.  Currently the best solution seems to be the use of laser distance sensors (a.k.a., 1-D lidar) to identify obstacles, and either haptic (vibration motors similar to what is in cell phones) or sonic feedback.

## Hardware

### Current Hardware:
* 4 VL53L0X sensors 1-D lidar detectors
* Raspberry Pi 4 - 4" x 2.7" x 1" - 900 mA draw
* 2 USB battery packs (20,000 mAH) - 6" x 3" x 0.6"
* 2 breadboards 1.5" x 2.0" x 1.4"
* 1 breadboard 6.5" x 2.2" x 1"
* various vibration motors
* various cables

Planned v0.5 hardware:
* 4 VL53L0X sensors 1-D lidar detectors
* Raspberry Pi Zero W - 3.1 x 1.6 x 0.4 - 250 mA draw
* 2 USB battery packs (5,000 mAH) - ??
* 2 sensor modules on standard prototype pcb - 1" x 1.5" x 0.8"
* various vibration motors
* ribbon cable with 2x20 IDC female connector in the middle

Planned v0.6 hardware:
* 4 VL53L0X sensors 1-D lidar detectors
* Raspberry Pi Zero - 3.1 x 1.6 x 0.4 - 100 mA draw - no wifi
* 2 USB battery packs (1,500 mAH) - ??
* 2 sensor modules on standard prototype pcb - 1" x 1.5" x 0.8"
* 1 breadboard 6.5" x 2.2"
* ribbon cable with 2x20 IDC female connector in the middle

Planned v0.7 hardware:
* 4 VL53L0X sensors 1-D lidar detectors
* seeeduino - 1.0" x 0.7" x 0.5" - 20 mA draw - "burned in ROM code"
* small power supply?? 1" 1" 0.5"
* 2 USB battery packs (500 mAH) - ??
* 2 sensor modules on standard prototype pcb - 1" x 1.5" x 0.8"
* 1 breadboard 6.5" x 2.2"
* various vibration motors
* custom ribbon cable


* VL53L0X sensors are $5 USD each (in low volume) and seem to work well at providing distance measurement from 30mm to 2000mm / 2m.
* various vibration motors can be had for less than $1 USD each
* ultrasonic or normal speakers can be sourced for $2 USD each
* current development (still prototyping) is using a Raspberry Pi 4 B.  Final product will likely be a Raspberry Pi Zero, or an Arduino or ESP8266.

Current size
[Challenges](Challenges/Challenges.md)

[Progress](Progress/Progress.md)
