
![image](https://github.com/user-attachments/assets/d8951da3-944f-453c-819f-6bc2c07d26c5)


# Autonomous Acoustic Piano Player

An ambitious real-world project that transforms a traditional 88-key acoustic piano into a fully automated, intelligent instrument — powered by a Raspberry Pi, ESP microcontroller, and 91 servo motors.

## Project Overview

This system allows a standard acoustic piano to play music on its own — no human touch required. A total of 88 micro servo motors are mounted above each key, acting as robotic fingers. Additionally, 3 extra servos control the piano’s pedal system.

The system listens to music played through a nearby speaker (e.g. from a smartphone), identifies the piano sounds, and then reproduces them in real-time by physically pressing the matching keys with the servos. The result is a natural and dynamic piano performance using real mechanical motion.

## Key Features

- Fully mechanical playback on a real acoustic piano
- Controlled by Raspberry Pi + ESP microcontroller
- 88 servo motors for keys + 3 for pedal control
- Real-time audio input analysis
- Responsive key-press system for dynamic sound


## How It Works

1. **Audio Detection:** The system listens to any song playing from nearby speakers.
2. **Note Recognition:** It detects piano notes using audio processing techniques (planned via Python + ML).
3. **Key Activation:** The corresponding servos rotate and tap keys, simulating a live performance.

## Current Status

- Mechanical prototype: In progress
- Electronics and servo frame: Design phase
- Software (note detection + control): Development ongoing
- Final assembly: Planned in the next few months

## Coming Soon

Once the project is complete, the following resources will be published:

- Source code (ESP + Raspberry Pi)
- 3D printable models for servo mounts
- Circuit diagrams and wiring guides
- Video demonstrations and setup instructions

Stay tuned!

---
*Made with love and servos.*
