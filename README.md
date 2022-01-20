# NoMoreBoopSnoot

A hardware and software system to assist blind canines with obstacle avoidance

An ongoing project to make blind dogs (and likely other animals) more confidnent and safer by providing Obstacle Avoidance warnings to the dog.  Currently the best solution seems to be the use of laser distance sensors (a.k.a., 1-D lidar) to identify obstacles, and either haptic (vibration motors similar to what is in cell phones) or sonic feedback.

Hardware (current):
* VL53L0X sensors are $5 USD each (in low volume) and seem to work well at providing distance measurement from 30mm to 2000mm / 2m.
* various vibration motors can be had for less than $1 USD each
* ultrasonic or normal speakers can be sourced for $2 USD each
* current development (still prototyping) is using a Raspberry Pi 4 B.  Final product will likely be a Raspberry Pi Zero, or an Arduino or ESP8266.

[Challenges](Challenges.md)
