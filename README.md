# Project-AETHER
An Artificially Enhanced Telescope for Heuristic Ephemeris Recognition

## Overview

This project aims to develop an intelligent, precision-controlled telescope system that leverages embedded systems, AI, and custom mechanical design to track celestial bodies with minimal user input. The system is designed with practical constraints in mind—cost-efficiency, power awareness, and full usability as an optical telescope.

## Objectives

- Develop a fully functional telescope mount capable of precise movement across both axes.
- Integrate inertial measurement units (IMUs) to provide orientation feedback.
- Implement a control system to accurately align with planets and stars using real-time ephemeris data.
- Incorporate AI to enhance prediction and correction capabilities during object tracking.
- Design a custom actuator to optimize performance, reduce cost, and minimize energy consumption.

## Key Features

- **AI-Powered Tracking**: Trained models aid in predicting object movement and compensate for mechanical drift.
- **Sensor Fusion**: Combines IMU data with celestial coordinate calculations for intelligent orientation correction.
- **Modular Architecture**: Designed for scalability and hardware flexibility—supports STM32 microcontrollers and FPGAs.
- **Custom Actuator Design**: Focused on mechanical precision, affordability, and energy efficiency.
- **Telescope Usability Maintained**: All enhancements preserve the telescope’s primary function without compromising optical alignment.

## Why It Matters

Affordable, intelligent tracking telescopes are essential tools in education, amateur astronomy, and field research. This project explores the intersection of AI, control systems, and embedded engineering to develop an open, accessible, and research-grade solution.

## Hardware Involved

- STM32 Microcontroller (Nucleo or STM32N6 series)
- IMU Sensor (e.g., MPU-6050, BNO055)
- Stepper Motor Driver (e.g., TMC2209, A4988)
- Optional FPGA Acceleration
- Real-Time Clock (e.g., DS3231)
- Custom Actuator Prototype
- Telescope (refractor or reflector with equatorial/alt-az mount)

## Software Stack

- STM32CubeMX + STM32CubeIDE
- STM32Cube.AI
- Edge Impulse (for AI model training)
- C/C++ for firmware development
- Optional: Python/Matplotlib for data analysis and testing

## Applications

- Educational observatories
- Remote and automated observatories
- Research-grade sky tracking for amateur astronomers
- A foundation for low-cost satellite tracking platforms

## Goals

This project is part of a broader vision: to blend embedded systems design with aerospace-inspired control solutions. By combining traditional engineering with AI, it seeks to prove that cost-effective, intelligent hardware systems can be both highly functional and academically valuable.

## Future Work

- Integration of vision-based fine-tuning using telescope-mounted astrophotography cameras.
- Real-time data logging and visualization.
- Expansion into satellite object tracking.
- Publication of results in embedded systems and AI in astronomy.

## License

This project will be released under an open-source license (TBD). Contributions are welcome.

---

**Developed by a Computer Science undergraduate specializing in embedded systems and intelligent hardware design.**
