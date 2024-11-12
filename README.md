# Capstone-Project
# Phase Locked Loop (PLL) for Clock Generation in SerDes

## Overview
This project involves designing a high-performance Phase Locked Loop (PLL) for Serializer/Deserializer (SerDes) systems using 180nm CMOS technology. Developed as a capstone project, this PLL system is aimed at providing stable and low-jitter clock generation for data serialization, essential for high-speed data transmission in communication systems.

## Table of Contents
- [Specifications](#specifications)
- [Tools Used](#tools-used)
- [What is a PLL?](#what-is-a-pll)
- [Components](#components)
  - [Phase Frequency Detector](#phase-frequency-detector)
  - [Charge Pump](#charge-pump)
  - [Voltage Controlled Oscillator](#voltage-controlled-oscillator)
  - [Frequency Divider](#frequency-divider)
- [Schematics](#schematics)
  - [Phase Frequency Detector Schematic](#phase-frequency-detector-schematic)
  - [Charge Pump Schematic](#charge-pump-schematic)
  - [Voltage Controlled Oscillator Schematic](#voltage-controlled-oscillator-schematic)
  - [Complete PLL Schematic](#complete-pll-schematic)
- [Output Waveforms](#output-waveforms)
  - [Transient Response](#transient-response)
  - [Steady State Response](#steady-state-response)
  - [Output Frequency](#output-frequency)

## Specifications

| Parameter         | Value               |
|-------------------|---------------------|
| VDD               | 1.8 V               |
| Frequency Range   | 1 GHz - 3 GHz       |
| Duty Cycle        | 50%                 |
| Jitter            | < 25 ps             |
| Locking Time      | < 5 µs              |
| Corner            | TT                  |
| Temperature       | Room Temperature    |

## Tools Used
- Cadence Virtuoso
- Spectre

## What is a PLL?
A Phase Locked Loop (PLL) is an electronic circuit that synchronizes an output signal with a reference signal in frequency and phase. It’s widely used in applications like SerDes, where stable clock generation is critical for data transmission.

## Components

### Phase Frequency Detector
The PFD detects the phase difference between the reference clock and the divided clock and generates output signals to drive the charge pump.

### Charge Pump
The charge pump converts phase error signals into control voltage, stabilizing the VCO output.

### Voltage Controlled Oscillator
The VCO produces a high-frequency clock signal that matches the reference clock frequency.

### Frequency Divider
The frequency divider reduces the output frequency to maintain synchronization with the reference clock.

## Schematics

### Phase Frequency Detector Schematic
![Phase Frequency Detector Schematic](path/to/your/phase_frequency_detector_schematic.png)

### Charge Pump Schematic
![Charge Pump Schematic](path/to/your/charge_pump_schematic.png)

### Voltage Controlled Oscillator Schematic
![Voltage Controlled Oscillator Schematic](path/to/your/vco_schematic.png)

### Complete PLL Schematic
![Complete PLL Schematic](path/to/your/complete_pll_schematic.png)

## Output Waveforms

### Transient Response
![Transient Response](path/to/your/transient_response.png)

### Output Frequency
![Output Frequency](path/to/your/transient_response.png)


