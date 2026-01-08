# ultrasonic-led-fader

# Ultrasonic LED Fader with Filtering

## Overview
This project implements a proximity-based LED indicator using an ultrasonic sensor.
LED brightness varies smoothly with distance, using filtering and PWM to provide
stable and responsive visual feedback.

## Features
- Ultrasonic distance measurement
- Exponential smoothing to reduce noise
- Distance clamping and linear mapping
- Smooth LED fading using PWM
- Fully documented hardware and software design

## Hardware
- Arduino Uno R3
- HC-SR04 ultrasonic sensor
- LED + current-limiting resistor

## Behavior
- LED off beyond 20 cm
- LED brightness increases between 20 cm and 10 cm
- LED fully on at 10 cm or closer
- Smooth transitions with no visible flicker

## Documentation
Detailed documentation, schematics, wiring diagrams, and a demo video are available
in the `docs/` folder.

## Status
Completed – Version 1.0
