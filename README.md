# Arduino Temperature Monitoring

## Project Description

This project is a simple Arduino-based temperature monitoring system using an LM35 temperature sensor.

The Arduino reads the analog value from the temperature sensor, converts it into temperature in Celsius, and displays the result through the Serial Monitor.

## Hardware Requirements

- Arduino Uno
- LM35 Temperature Sensor
- Jumper Wires
- Breadboard
- USB Cable

## Software Requirements

- Arduino IDE
- Arduino Uno board
- Serial Monitor

## How It Works

1. The LM35 sensor measures the surrounding temperature.
2. Arduino reads the analog sensor value from pin A0.
3. The analog value is converted into voltage.
4. The voltage is converted into temperature in Celsius.
5. The temperature is displayed on the Serial Monitor every second.

## Quality Assurance

The project will be tested for:

- Incorrect temperature readings
- Sensor connection problems
- Incorrect serial communication settings
- Unclear output messages
- Incorrect sensor calculations
