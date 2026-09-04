# Op-Amp Differential Amplifier System Analysis

![LTspice](https://img.shields.io/badge/Simulation-LTspice-blue)
![Project](https://img.shields.io/badge/Field-Electrical%20Engineering-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Overview

This project presents a comprehensive electrical analysis and simulation of an operational amplifier differential amplifier system using LTspice.

The objective of this work is to investigate the dynamic and steady-state behavior of the amplifier circuit through different simulation approaches, including transient response, frequency behavior, impulse response, input impedance evaluation, and power analysis.

The complete circuit model, simulation files, documentation, presentation materials, and obtained results are included in this repository.

---

# Circuit Description

The analyzed system consists of:

- Operational amplifier model
- Differential input configuration
- Feedback network
- Resistive and capacitive elements
- Input signal sources
- Output loading network

The circuit behavior is studied under different excitation conditions to evaluate amplifier performance and stability.

---

# Simulation Environment

## Software

- LTspice XVII

## Analysis Methods

The following simulations were performed:

### 1. Transient Analysis

Evaluation of the time-domain response of the amplifier system.

Purpose:

- Observe dynamic behavior
- Analyze charging/discharging effects
- Evaluate settling characteristics


### 2. Step Response Analysis

The response of the system to a step input signal was investigated.

Parameters evaluated:

- Rise behavior
- Output transition
- System stability


### 3. Impulse Response Analysis

The impulse response was simulated to study the natural response characteristics of the amplifier.

This analysis helps evaluate:

- Dynamic properties
- System response speed
- Transient characteristics


### 4. Sinusoidal Response Analysis

A sinusoidal input signal was applied to analyze:

- Output waveform behavior
- Gain characteristics
- Signal reproduction quality


### 5. Input Impedance Analysis

The input impedance of the system was evaluated by applying test signals and analyzing the resulting voltage-current relationship.

---

# Simulation Results

The obtained results include:

## Output Voltage Response

Analysis of the output waveform under different input conditions.

## Input Current Behavior

Evaluation of current variations during operation.

## Transient Characteristics

Investigation of:

- Initial response
- Stabilization time
- Dynamic behavior


## Power Analysis

Power behavior of circuit elements was evaluated, including capacitor energy interaction and load characteristics.

---

# Repository Structure

```
OpAmp-Differential-Amplifier-System-Analysis

│
├── Documentation
│   ├── Project_Report.pdf
│   └── README.md
│
├── Images
│   ├── Circuit Diagram
│   ├── Simulation Results
│   └── Graphs
│
├── LTspice
│   ├── OpAmp_Differential_Amplifier.asc
│   └── Simulation Files
│
├── Presentation
│   ├── Project Presentation.pdf
│   └── Project Presentation.pptx
│
└── README.md
```

---

# Circuit Diagram

The LTspice schematic file is provided in the `LTspice` directory.

Users can open the `.asc` file directly in LTspice and reproduce the simulations.

---

# Results Preview

Simulation outputs include:

- Transient response plots
- Step response plots
- Impulse response plots
- Sinusoidal waveform analysis
- Input current measurements
- Power evaluation graphs

Detailed images are available in the `Images` directory.

---

# Documentation

A complete project report is provided containing:

- Circuit explanation
- Mathematical analysis
- Simulation procedure
- Results discussion
- Conclusions

Available in:

```
Documentation/Project_Report.pdf
```

---

# Presentation

Presentation files are included for academic demonstration:

```
Presentation/
```

Formats:

- PDF
- PowerPoint (.pptx)

---

# Conclusion

The project demonstrates the application of LTspice simulation techniques for analyzing an operational amplifier differential amplifier system.

Through multiple simulation methods, the electrical behavior, dynamic response, stability characteristics, and performance parameters of the circuit were investigated.

---

# Author

**Arghavan Memari**

Electrical Engineering Project

---

# License

This project is provided for educational and research purposes.
