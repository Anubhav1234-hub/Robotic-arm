# 5-DOF Robotic Arm Controller (Bluetooth & Serial)

An Arduino-based control system for a 5-Degree of Freedom (DOF) robotic arm. This project supports manual control via a custom MIT App Inventor Android application (Bluetooth HC-05) and direct Serial Monitor commands.

## Features
* **Multi-Mode Control:** Use sliders on a mobile app or type commands in the Arduino Serial Monitor.
* **5-Joint Support:** Controls Shoulder, Elbow, Wrist Pitch, Wrist Roll, and Gripper.
* **Neutral Start:** Servos automatically initialize to 90 degrees to prevent mechanical strain.

## Hardware Components
* Arduino Uno / Nano
* 5x Servo Motors (2:-mg968R AND 3:-Mini Servo)
* HC-05 Bluetooth Module
* External Power Supply (Lithioum Ion)
* Connecting Wires

## Command Syntax
Commands are sent as a Letter + Number (0-180):
- `S[angle]` : Shoulder
- `E[angle]` : Elbow
- `P[angle]` : Wrist Pitch
- `R[angle]` : Wrist Roll
- `G[angle]` : Gripper# Robotic-arm
This project is a complete hardware and software solution for controlling a 5-Degree of Freedom (DOF) robotic arm. It features a custom-built Android application created with MIT App Inventor that communicates over Bluetooth to an Arduino Uno.
