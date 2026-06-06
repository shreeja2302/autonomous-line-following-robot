# Autonomous Line-Following Robot

An Arduino-based autonomous robot engineered for stable real-time line tracking using PID control, auto-calibration, and sharp-turn recovery logic.

---

## Overview

This project involved the full hardware and software design of an autonomous line-following robot capable of navigating complex paths with precision and reliability. The robot uses IR sensors for real-time path detection and a PID controller for smooth, responsive motor correction — achieving sub-50ms sensor response time and 30-minute battery endurance.

---

## Key Features

- PID control (Kp=18, Kd=25) for real-time path correction
- Auto-calibration routine for varying surface and lighting conditions
- 90° sharp-turn recovery logic for complex track navigation
- Sub-50ms sensor response time
- 30-minute continuous battery endurance
- 4-motor drive system on a 7.4V–9V chassis

---

## Hardware Components

| Component | Details |
|---|---|
| Microcontroller | Arduino Nano |
| Motor Driver | L298N Dual H-Bridge |
| Sensors | 2x IR Sensors |
| Drive System | 4 Motors |
| Power Supply | 7.4V – 9V Chassis Battery |

---

## How It Works

1. **Sensing** — IR sensors detect the line on the surface and feed positional data to the Arduino in real time
2. **PID Control** — The controller computes error from the line center and adjusts motor speeds accordingly to correct the path
3. **Auto-Calibration** — On startup, the robot calibrates sensor thresholds to adapt to surface and ambient light conditions
4. **Turn Recovery** — Custom logic detects and handles 90° sharp turns that would otherwise cause the robot to lose the line

---

## Performance

| Metric | Result |
|---|---|
| Sensor Response Time | < 50ms |
| Battery Endurance | 30 minutes |
| Turn Handling | 90° sharp turns |
| Drive Configuration | 4-motor, dual H-bridge |

---

## Author

**Shreeja Saha Roy**  
B.Tech Computer Science & Engineering, KIIT Bhubaneswar  
[LinkedIn](https://www.linkedin.com/in/shreeja-saha-roy/) · 
