# ESP32IoTPlatform

[![Version](https://img.shields.io/github/v/release/jkordek1/ESP32IoTPlatform)](https://github.com/jkordek1/ESP32IoTPlatform/releases/tag/Initial)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/jkordek1/ESP32IoTPlatform)](https://github.com/jkordek1/ESP32IoTPlatform/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/jkordek1/ESP32IoTPlatform)](https://github.com/jkordek1/ESP32IoTPlatform/pulls)


## What is it?
ESP32IoTPlatform is an open source platform aimed towards students at Zagreb University of Applied Sciences who will take the IoT course.
It enables quick and easy firmware development thanks to built in sensors, actuators and other electronic components.

## Features
- Based on dual-core ESP32 microcontroller module
- External battery connector
- Battery charging via microUSB cable
- Buzzer for audio queues
- HC-SR04 ultrasonic sensor connector
- MOSFET output
- Relay output
- LDR
- Potentiometer
- 1.3" OLED screen
- microSD slot
- accelerometer & gyro
- BME280 temperature and humidity sensor
- GPS module
- WS2812-B RGB LEDs
- Touchad
- Joypad

## Images
<p align="center">
 <img width="800" src="https://raw.githubusercontent.com/jkordek1/ESP32IoTPlatform/main/Images/Final_front.PNG">
</p>

## Project folder structure
    .
    ├── ...
    ├── Images                  # Images of the project
    ├── Output files            # Gerber files
    ├── KiCadFiles              # Main folder
    │   ├── 3d modeli           # 3D models of added components
    │   ├── Board2Pdf           # Assembly files
    │   ├── bom                 # ibom assembly files
    │   └── gerber              # gerber
    ├── Schematic.pdf           # Schematic .pdf file
    └── ...
