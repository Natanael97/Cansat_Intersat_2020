# CanSat Intersat 


## Overview
This project presents the design, development, and testing of a CanSat system created as part of an aerospace competition organized by UNAM. The system was designed to collect, transmit, and analyze environmental data in real time while ensuring structural integrity during high-altitude deployment and impact.

## Objective
To design a compact satellite system capable of:
- Acquiring environmental data (temperature, pressure, acceleration)
- Transmitting data wirelessly to a ground station
- Withstanding impact after descent
- Maintaining system integrity throughout the mission

## System Architecture

The system was divided into two main subsystems:

### 1. Data Acquisition System
- Microcontroller: PIC18F2550
- Sensors:
  - Temperature (LM35)
  - Pressure (MPX4115)
  - Accelerometer (GY-61)
- Multi-channel analog data processing

### 2. Communication System
- XBee modules (RF communication)
- Serial communication protocol
- Real-time data transmission to ground station

### 3. Ground Station
- Data reception via XBee
- Data processing and visualization using LabVIEW
- Real-time monitoring interface

## Mechanical Design

- Modular electronic architecture (multi-layer PCB design)
- External structure designed using Autodesk Inventor
- Manufactured using 3D printing (ABS material)
- Impact resistance validated through simulation

The structural design was inspired by natural aerodynamic systems (e.g., seed fall dynamics) to reduce descent speed and improve stability.

## Simulation & Analysis

- Stress simulations performed (ABS vs Aluminum)
- Impact force estimated: ~207,000 N
- Structural optimization based on weight, cost, and manufacturability

## Results

- Successful real-time transmission of **814 data packets without interruption**, even after impact :contentReference[oaicite:0]{index=0}  
- Maximum recorded altitude: ~379 m :contentReference[oaicite:1]{index=1}  
- Stable system performance during ascent, descent, and landing  
- Functional recovery system (buzzer)

## Key Learnings

- Integration of embedded systems with RF communication
- Trade-offs between structural resistance and weight
- Importance of modular design in constrained environments
- Real-world validation of simulation models

## Repository Contents

- Technical report (Spanish)
- Design files and simulations
- System diagrams
- Experimental results
- Project documentation

## Note
This repository includes original documentation in Spanish. Summaries and explanations are provided in English for accessibility.

## Future Improvements

- Integration of GPS for real-time tracking
- Aerodynamic optimization using wind tunnel simulations
- Enhanced energy efficiency strategies
- Improved sensor accuracy and calibration

## Author
Developed Intersat – UNAM

<img width="835" height="623" alt="LogoCANSAT-BW-02" src="https://github.com/user-attachments/assets/fe11a9c5-65c7-4518-94a0-d64a045291b9" />
