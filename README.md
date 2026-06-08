# Smart Street Light using Arduino + IoT

## Project Overview
An automated street lighting system using Arduino Uno, LDR, PIR sensor and ESP8266 WiFi module.

## Features
- Auto ON/OFF based on light intensity (LDR)
- Motion detection using PIR sensor
- IoT monitoring via ESP8266
- Energy saving - light only ON when needed

## Components Required
| Component | Quantity |
|---|---|
| Arduino Uno | 1 |
| LDR Sensor | 1 |
| PIR Motion Sensor | 1 |
| LED | 1 |
| Relay Module | 1 |
| ESP8266 WiFi Module | 1 |
| Resistor 10kΩ | 1 |
| Jumper Wires | As needed |
| Breadboard | 1 |

## Circuit Connections
| Component | Arduino Pin |
|---|---|
| LDR | A0 |
| PIR Sensor | Pin 7 |
| LED/Relay | Pin 8 |
| ESP8266 TX | Pin 2 |
| ESP8266 RX | Pin 3 |

## How It Works
1. LDR detects darkness - system activates at night
2. PIR sensor detects motion
3. LED turns ON when motion detected at night
4. LED turns OFF when no motion
5. ESP8266 sends status to IoT cloud

## How to Use
1. Upload `smart_street_light.ino` to Arduino Uno
2. Connect components as per circuit connections
3. Power the Arduino
4. Monitor via Serial Monitor at 9600 baud rate
