# Arduino Motion Detection Alarm

## Overview
This project is a simple motion detection alarm built using an Arduino Uno, a PIR motion sensor, LEDs, and a piezo buzzer. When motion is detected, the Arduino activates visual and audible alerts.

## Features
- Detects motion using a PIR sensor
- Turns on LEDs when motion is detected
- Sounds a piezo buzzer alarm
- Displays motion status on the Serial Monitor

## Components Used
- Arduino Uno
- PIR Motion Sensor (HC-SR501)
- Piezo Buzzer
- 2 LEDs
- 2 × 220 Ω Resistors
- Breadboard
- Jumper Wires
- Tinkercad Software

## Circuit
The circuit was designed and simulated using Tinkercad.

## How It Works
1. The PIR sensor monitors for movement.
2. When motion is detected, it sends a HIGH signal to the Arduino.
3. The Arduino turns on the LEDs and activates the buzzer.
4. When no motion is detected, the alarm is turned off.

## Technologies Used
- Arduino IDE
- C++
- Tinkercad

## Future Improvements
- Add an LCD display
- Send notifications via Bluetooth or Wi-Fi
- Include a countdown timer before the alarm activates
- Power the system using a battery

## Author
**Manha Sindha**
