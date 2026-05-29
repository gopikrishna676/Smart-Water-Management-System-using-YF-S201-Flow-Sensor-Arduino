# Smart Water Management System using YF-S201 Flow Sensor & Arduino

## Overview
This project is a real-time smart water monitoring and control system developed using the YF-S201 water flow sensor and Arduino. The system continuously measures water consumption and implements an automated protection mechanism to reduce excessive water usage.

The project was designed with reference to BIS (Bureau of Indian Standards) water usage guidelines issued by the Government of India, promoting efficient and responsible water management.

---

## Objectives
- Monitor real-time water flow and total water consumption
- Alert users when water usage exceeds a predefined limit
- Automatically stop water supply at critical usage levels
- Encourage water conservation through automation

---

## Features

### Real-Time Flow Monitoring
The YF-S201 Hall-effect flow sensor measures water flow rate and total water consumption continuously.

### Dual-Threshold Protection System
The system implements two levels of protection:

#### Threshold 1 — Warning Stage
- A buzzer alert is activated when water consumption crosses the first predefined limit.
- Warns users about excessive or abnormal water usage.

#### Threshold 2 — Automatic Cutoff Stage
- A solenoid valve is triggered when water usage exceeds the second critical threshold.
- Water supply is automatically shut off to prevent wastage or leakage.

### Embedded System Control
Arduino is used as the main controller for:
- Pulse counting from the flow sensor
- Flow rate calculations
- Threshold comparison logic
- Actuation of buzzer and solenoid valve

---

## Components Used
- Arduino Uno
- YF-S201 Water Flow Sensor
- Solenoid Valve
- Buzzer
- Relay Module
- Power Supply
- Connecting Wires and Tubing

---

## Working Principle
The YF-S201 sensor generates pulses proportional to the water flow rate. Arduino reads these pulses and calculates:
- Instantaneous flow rate
- Total water consumed

The calculated values are continuously compared against predefined thresholds:
1. If consumption exceeds Threshold 1:
   - Buzzer warning is activated
2. If consumption exceeds Threshold 2:
   - Solenoid valve closes automatically

This creates an intelligent water management mechanism capable of monitoring and controlling consumption in real time.

---

## Applications
- Smart homes
- Water conservation systems
- Residential water monitoring
- Industrial water usage tracking
- Automated leakage prevention systems

---

## Future Improvements
- IoT-based remote monitoring
- Mobile app integration
- Cloud data logging and analytics
- LCD/OLED live display
- AI-based water usage prediction

---

## Technologies Used
- Arduino IDE
- Embedded C/C++
- Sensor interfacing
- Automation and control systems

---

## Project Outcome
The project successfully demonstrated an automated smart water management solution capable of:
- Monitoring water usage in real time
- Providing user alerts
- Automatically controlling water supply
- Supporting water conservation initiatives
