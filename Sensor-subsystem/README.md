# Robot Sensor Subsystem
## Overview
This repository contains the design, implementation, and integration details of the sensor subsystem for a robot project. The sensor subsystem is responsible for detecting obstacles in front, to the left, and to the right of the robot, providing essential information for navigation and obstacle avoidance.

## Features
Obstacle Detection: Uses IR sensors to detect obstacles in three directions: front, left, and right.
Power Management: Implements MOSFET switches to enable/disable sensors, conserving battery power when sensors are not in use.
Visual Indication: Uses LEDs on the processor board to indicate the presence of obstacles.
High Reliability: Designed with redundant ground planes, decoupling capacitors, and other failure management processes to ensure robust operation.

## System Integration
The sensor subsystem integrates with the main robot system through a 2x14 pin header connection. It interfaces with the robot's processor to provide obstacle detection data and receive power management signals.

## Power Management
To ensure efficient power usage, the subsystem employs MOSFET switches controlled by PWM signals from the processor. This allows the sensors to be powered only when needed, conserving battery life.

## Components
IR Sensors: Detect obstacles by emitting and detecting infrared light.
MOSFETs: Switch the power supply to the sensors on and off.
Microcontroller: Reads sensor data and controls MOSFETs and LEDs.
LEDs: Indicate the presence of obstacles.

## Software
The software interfaces the sensor subsystem with the rest of the robot's system, handling sensor readings, power management, and LED indications.

## Getting Started
Hardware Setup: Assemble the sensor subsystem on the PCB and connect it to the robot's processor board using the 2x14 pin header.
Software Setup: write code to the microcontroller to start interfacing with the sensors.
Testing: Use the LEDs to verify that the sensors are correctly detecting obstacles.

# License
This project is licensed under the MIT License - see the LICENSE file for details.
