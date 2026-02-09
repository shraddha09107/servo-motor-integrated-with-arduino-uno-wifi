# Servo Motor Control Project

## Overview
This project demonstrates basic servo motor control using an Arduino microcontroller. The servo rotates through a predefined sequence of angles with configurable delays.

## Hardware Requirements
- Arduino microcontroller (Uno, Mega, etc.)
- Servo motor
- Jumper wires
- Power supply (5V recommended for servo)

## Pin Configuration
- **Servo Signal Pin**: PIN 9

## Libraries Used
- `Arduino.h` - Core Arduino functionality
- `Servo.h` - Servo motor control library

## How It Works
The program controls a servo motor through the following motion sequence:

1. **Forward Motion**: Rotates from 0° to 180° in 40° increments (15ms between steps)
2. **Reverse Motion**: Rotates from 180° to 0° in 90° increments (15ms between steps)

The loop repeats continuously.

## Setup Instructions
1. Connect the servo motor signal wire to PIN 9 on your Arduino
2. Connect the servo power and ground wires to appropriate power supply
3. Upload the code to your Arduino board
