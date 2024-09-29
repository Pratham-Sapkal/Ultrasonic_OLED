# Distance Measurement Using Ultrasonic Sensor, OLED Display, and Arduino Nano

This project measures the distance using an ultrasonic sensor and displays the value on an OLED screen using an Arduino Nano.
## [YouTube Tutorial](https://youtube.com/shorts/t0S9802IDw4)

## Components Required
- Arduino Nano
- Ultrasonic Sensor (HC-SR04)
- OLED Display (e.g., SSD1306 128x64)
- Jumper wires
- Breadboard (optional)
- Power supply (e.g., USB cable or battery)

## Wiring Connections
1. **Ultrasonic Sensor to Arduino Nano:**
   - VCC → 5V
   - GND → GND
   - Trig → Digital Pin 9
   - Echo → Digital Pin 10

2. **OLED Display to Arduino Nano:**
   - VCC → 3.3V
   - GND → GND
   - SCL → A5 (SCL)
   - SDA → A4 (SDA)

## Software Setup
1. Install the **Adafruit SSD1306** library for the OLED display.
2. Install the **Adafruit GFX** library, which is required by the SSD1306 library.

## Upload the Given Code 
## Explanation
- The ultrasonic sensor works by emitting a sound wave and measuring the time it takes for the echo to return. The distance is calculated based on the speed of sound.
- The OLED display is used to show the distance in real-time.
- The code calculates the distance and then updates the OLED display at regular intervals.
