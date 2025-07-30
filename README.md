# Bluetooth_home_automation

## Home Automation System using Arduino (Serial Monitor Controlled)

This is a simple simulation of a Home Automation System using an Arduino Uno. The system allows users to control two appliances — a Light and a Fan — via serial commands sent from the Serial Monitor.

# Features

 Control Light (Red LED)
 Control Fan (Green LED)
 Serial-based command interface
 Simple and beginner-friendly code
 Tinkercad compatible

# Components Used

Arduino Uno
Red LED (Light)
Green LED (Fan)
220Ω Resistors (x2)
Jumper Wires
USB cable (for power and serial communication)

# How It Works

The system reads commands via the Serial Monitor:
Send 1 → Light ON (Red LED)
Send 2 → Light OFF
Send 3 → Fan ON (Green LED)
Send 4 → Fan OFF
Any other input will return an "Invalid Command" message.

# Setup Instructions
Connect components as shown in the diagram.
Upload the code to the Arduino Uno.
Open the Serial Monitor (set baud rate to 9600).
Type 1, 2, 3, or 4 and press Enter to control devices.

# Applications

Basic home automation simulations
Arduino learning projects
Bluetooth control extension (future upgrade)

# Created by M.Janani
