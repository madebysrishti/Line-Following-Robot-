# Line Following Robot

## Overview
An autonomous robot that follows a predefined path using IR sensor-based line detection and differential motor control.

## Components Used
- Arduino Nano
- IR Sensor Module (x2 or x3, mention exact number)
- L298N Motor Driver
- DC Motors
- Chassis
- Battery Pack

## Working Principle
The IR sensors detect contrast between the line and background surface. Based on sensor output, the microcontroller adjusts motor speed to maintain alignment with the path.

## Control Logic
- If left sensor detects line → turn left
- If right sensor detects line → turn right
- If both detect → move forward
- If none detect → stop / search

## Concepts Applied
- Digital Input Processing
- Conditional Logic
- PWM Motor Control
- Embedded C Programming

## Challenges Faced
- Sensor calibration
- Speed vs stability trade-off
- Surface reflection issues

## Improvements (Future Scope)
- PID-based smoother control
- Speed optimization
- Multi-sensor array upgrade
