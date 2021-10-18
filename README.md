# I2C Master for ATMega328P co-processor for Raspberry Pi

This is for a board that controls some LEDs, power buttons and a tilt server. It also adds current measurement and handling the UPS.

This is more or less a private project, but maybe someone is interested in looking at the source code.
I have added a few comments to get a better understanding and described issues I ran into.

*** this is work in progress, the feature list is not completely implemented yet. probably finished in a week or two ***

## I2C Master (Python/Raspberry Pi)

 - Read voltage, current, power and energy consumption
 - 5V rail voltage and current monitoring
 - UPS low battery shutdown
 - Control fan or set to auto mode
 - LED animations
 - Control tilt servo
 - Buzzer control
 - MQTT support for recording metrics

## I2C Slave (C++/AVR)

(https://github.com/sascha432/pi_control)[https://github.com/sascha432/pi_control]
