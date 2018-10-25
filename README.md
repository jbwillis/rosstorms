# ROSSTORMS
Hardware and Software for combining the power of the Robot Operating System with the ease of use of LEGO Mindstorms motors and sensors.

## Hardware
To avoid the clunky and expensive LEGO brick, an expandable circuit board with 4 motor ports, 4 sensor ports, as well as other interfaces for non LEGO sensors and actuators. 

### Possible Features
* Grove board support
* Arduino shield support
* Raspberry pi header support
* USB (versus serial only)

## Firmware
Uses rosserial to communicate with master controller. Data that is reported is set up by master upon initialization.

### Possible Data
* Motor 1, 2, 3 
  * drive setting
  * tachometer count
  
### Possible Commands
* Motor 1, 2, 3
  * drive setting
  * reset tach
  * enable/disable data tx

## Software
The software is meant to run on a Linux machine with ROS. If the user desires to not use ROS, it is also possible to write python programs for rosstorms.


