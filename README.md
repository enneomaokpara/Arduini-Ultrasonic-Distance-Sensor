# Arduino Ultrasonic Distance Sensor

A simple Arduino project using the HC-SR04 ultrasonic sensor to measure distance and control an LED.

## Hardware Setup
<img width="4284" height="5712" alt="IMG_6884" src="https://github.com/user-attachments/assets/76f62f4c-cd37-4c97-a329-fe13a9d1f0e1" />
<img width="2360" height="1168" alt="IMG_0964" src="https://github.com/user-attachments/assets/186a35ff-d530-4664-a346-2b42dfd37515" />
<img width="4284" height="5712" alt="IMG_6883" src="https://github.com/user-attachments/assets/cc5a3e6b-e3d8-4265-ad4d-bc9177b0ec10" />

## Components
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- LED
- 220Ω Resistor
- Breadboard
- Jumper Wires

## Features
- Measures distance in centimeters
- Displays distance in Serial Monitor
- Turns LED on when an object is within 20 cm

## Wiring
Trig -> Pin 9
Echo -> Pin 10
LED -> Pin 13
GND -> GND

## Future Improvements
- Add buzzer for distance alarm
- Add multiple LEDs for distance ranges
- Integrate with robot car platform
