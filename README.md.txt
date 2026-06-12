# Automatic Dustbin Using Arduino Uno and Ultrasonic Sensor

## Overview

This project demonstrates a touchless automatic dustbin using an Arduino Uno, HC-SR04 ultrasonic sensor, and SG90 servo motor. The ultrasonic sensor detects a nearby hand or object and automatically opens the dustbin lid. After a short delay, the lid closes automatically, providing a hygienic waste disposal solution.

## Features

* Touch-free operation
* Automatic lid opening and closing
* Low-cost implementation
* Easy to build and maintain
* Suitable for homes, offices, and classrooms

## Components Used

* Arduino Uno
* HC-SR04 Ultrasonic Sensor
* SG90 Servo Motor
* Breadboard
* Jumper Wires
* USB Power Supply

## Working Principle

1. The ultrasonic sensor continuously measures the distance to nearby objects.
2. When an object is detected within a predefined range, the Arduino sends a signal to the servo motor.
3. The servo motor rotates and opens the dustbin lid.
4. After a short delay, the servo returns to its original position and closes the lid.

## Circuit Connections

### HC-SR04 Ultrasonic Sensor

* VCC → 5V
* GND → GND
* Trig → Arduino Digital Pin
* Echo → Arduino Digital Pin

### SG90 Servo Motor

* VCC → 5V
* GND → GND
* Signal → Arduino PWM Pin



## Applications

* Smart homes
* Hospitals
* Offices
* Educational projects
* Public hygiene systems

## Future Improvements

* Battery-powered operation
* IoT monitoring
* Waste-level detection
* Mobile app integration

## Author

Azmi Al Fatehin
