# Arduino Human-Following Robot

## Overview
This project is an Arduino-based mobile robot designed to follow a human using sensors while carrying small loads. The robot combines mechanical design, electronics, and programming to create an autonomous system capable of movement and object transportation.

## Objective
To design and build a robot that can:
- Detect and follow a person
- Move in multiple directions (forward, left, right)
- Carry and pull objects
- Avoid obstacles using sensors

## Inspiration
The project was inspired by real-world robotic systems such as smart luggage that can follow users automatically. Our goal was to create a simplified version of such assistive robotics technology. :contentReference[oaicite:0]{index=0}

## Components Used
- Arduino Uno
- Motor driver shield
- 4x TT gear motors
- 8x wheels
- Ultrasonic sensor
- Infrared sensors (2x)
- Servo motor
- Battery and battery holder
- Switch
- Jumper wires
- Wooden base

## System Design
The robot consists of:
- A wheeled base powered by DC motors
- Sensors mounted at the front to detect distance and movement
- A motor driver to control direction and speed
- Arduino acting as the main controller processing sensor data and controlling motion

According to the build process, all components (motors, sensors, and Arduino) were mounted on a base and connected through the motor driver shield. :contentReference[oaicite:1]{index=1}

## Methodology
1. Constructed the robot base and attached wheels and motors
2. Mounted Arduino and motor driver shield
3. Installed ultrasonic and infrared sensors for detection
4. Connected all electrical components using jumper wires
5. Uploaded Arduino code (sketch) to control movement
6. Tested the robot’s ability to follow a person and carry load

## Results
- The robot successfully followed a person using sensor input
- It was able to move in different directions based on movement
- It could carry up to approximately 1.16 kg
- The system responded to real-time environmental input

## Key Learnings
- Basics of Arduino programming and embedded systems
- Sensor integration and real-time decision making
- Mechanical assembly and system design
- Combining hardware and software into a functional system

## Conclusion
The robot successfully achieved its goal of following a human and transporting objects. This project demonstrates how simple components can be integrated into a functional robotic system with real-world applications in assistive technology. :contentReference[oaicite:2]{index=2}

## Future Improvements
- Improve tracking accuracy
- Add camera-based tracking
- Enhance obstacle avoidance
- Optimize power efficiency
