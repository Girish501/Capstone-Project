# Capstone-Project
# Phase Locked Loop (PLL) for Clock Generation in SerDes

## Overview
This project involves designing a high-performance Phase Locked Loop (PLL) for Serializer/Deserializer (SerDes) systems using 180nm CMOS technology. Developed as a capstone project, this PLL system is aimed at providing stable and low-jitter clock generation for data serialization, essential for high-speed data transmission in communication systems.

## Table of Contents
- [Project Objectives](#project-objectives)
- [Project Details](#project-details)
- [System Design](#system-design)
- [Key Features](#key-features)
- [Simulation Results](#simulation-results)
- [Future Work](#future-work)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

## Project Objectives
- **Generate a Stable Clock Signal**: Design a PLL capable of producing a stable, low-jitter clock signal for high-speed serial data transmission.
- **Optimize for SerDes Applications**: Develop a PLL system tailored for SerDes, employing a Phase Frequency Detector (PFD) and a dual-path loop filter.
- **Power Efficiency and Performance**: Incorporate resistorless loop filter designs to improve efficiency, reduce power consumption, and optimize performance.

## Project Details
- **Technology**: 180nm CMOS
- **Tools Used**: Cadence Virtuoso, Spectre
- **Team Members**: Girish Arora, Madhav Anand, Aayush Raj, Niyati Bhateja
- **Mentors**: Dr. Anil Singh, Dr. Alpana Agarwal

## System Design
The PLL system consists of several modules:

1. **Phase Frequency Detector (PFD)**: Detects the phase difference between the reference clock and the divided clock and generates output signals to drive the charge pump.
2. **Charge Pump and Loop Filter**: Converts phase error signals into control voltage, stabilizing the VCO output.
3. **Voltage Controlled Oscillator (VCO)**: Produces a high-frequency clock signal that matches the reference clock frequency.
4. **Frequency Divider**: Divides the output frequency to maintain synchronization with the reference clock.

### System Design Diagram
![System Design Diagram](path/to/your/system_design_diagram.png)

## Key Features
- **Dual-Path Loop Filter**: Enables refined frequency and phase adjustments for stability.
- **Resistorless Design**: Improves settling time, linearity, and power efficiency.
- **CMOS-Based Ring VCO**: Utilized for optimal frequency stability and performance.

## Simulation Results
Simulations were performed in Cadence Virtuoso to validate the performance of each module. Key metrics achieved:
- **Output Frequency**: Stable 4.44 GHz output achieved with low jitter.
- **Phase Noise**: Minimized phase noise, improving signal quality and stability.

### Block Diagram of SerDes System
![SerDes System Block Diagram](path/to/your/serdes_system_block_diagram.png)

### PLL Block Diagram
![PLL Block Diagram](path/to/your/pll_block_diagram.png)

### Circuit Schematic of PLL
![Circuit Schematic](path/to/your/circuit_schematic.png)

### Transient Response Simulation
![Transient Response](path/to/your/transient_response.png)

## Future Work
- **Prototyping and Testing**: Extend the design for physical prototyping and testing in real-world SerDes systems.
- **Optimization**: Further tuning for different process technologies and broader frequency ranges.

## Repository Structure
