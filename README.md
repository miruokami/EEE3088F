# Micro-mouse Project
## Project Overview
The Micro-mouse project focuses on designing and building subassemblies for a simplified micro-mouse, a maze-solving robot. 
This project involves creating hardware components with some minor software aspects, adhering to a strict budget.

## Project Modules
### Provided Modules
Motherboard: Connects all the PCBs together, serving as the base for other modules.
Processor: A STM32xxx processor board.

### Modules to Design and Manufacture
#### Power Module:
Responsibilities: Powering the entire system, running the motors, and charging the battery.
Requirements: Fit onto the motherboard pin headers, appropriate size for the robot, includes necessary connectors (e.g., JST PH 2mm pitch for the battery, 2x8 pin header for motherboard connection).

#### Sensor Module:
Responsibilities: Detecting and sensing objects.
Requirements: Fit onto the motherboard pin headers, appropriate size for the robot, utilize hysteresis for sensing, accurately sense different maze wall configurations.

## Demonstration Procedures
### Sensing Subsystem
Preparation: Bring a PCB, code ready to flash onto the STM32F0, and populated PCB.
Setup: Flash code, connect the necessary wires, plug sensing PCB into the testing PCB.
Testing: The sensor is supplied with power, and walls will be moved in various configurations to test the sensing accuracy.

### Power Subsystem
Preparation: Bring a PCB, and 4 spare PCBs.
Setup: Plug power PCB into the testing jig.

This README provides a concise overview of the Micro-mouse project, including project modules, and demonstration procedures. 
For comprehensive guidelines, please refer to the provided project description document .
