# Op-Amp Differential Amplifier System Analysis

![LTspice](https://img.shields.io/badge/Simulation-LTspice-blue)
![Electrical Engineering](https://img.shields.io/badge/Field-Electrical%20Engineering-green)
![Project Status](https://img.shields.io/badge/Status-Completed-success)

---

# Overview

This project presents the electrical analysis and LTspice simulation of an operational amplifier differential amplifier system.

The main purpose of this project is to investigate the dynamic and steady-state behavior of the amplifier circuit using different simulation techniques.

The analysis includes:

- Transient response
- Step response
- Impulse response
- Sinusoidal response
- Input impedance analysis
- Current analysis
- Power analysis

All simulation files, results, documentation, and presentation materials are included in this repository.

---

# Circuit Description

The designed system consists of:

- Operational amplifier model
- Differential input stage
- Feedback network
- Resistive elements
- Capacitive elements
- Input signal sources
- Output load

The circuit performance is evaluated under different input conditions to analyze stability, response characteristics, and electrical behavior.

---

# Simulation Environment

## Software

**LTspice XVII**

## Analysis Performed

### Transient Analysis

The time-domain response of the amplifier was investigated to observe:

- Dynamic behavior
- Stabilization process
- Output variation with time


### Step Response

The response of the system to a step input signal was analyzed.

Parameters evaluated:

- Rise behavior
- Output transition
- System response


### Impulse Response

The impulse response was simulated to study the natural dynamic characteristics of the circuit.

This analysis provides information about:

- System behavior
- Response speed
- Transient characteristics


### Sinusoidal Response

A sinusoidal input signal was applied to evaluate:

- Output waveform
- Signal reproduction
- Current behavior


### Input Impedance Analysis

The input impedance of the system was evaluated through voltage-current analysis.

---

# Circuit Schematic

The LTspice circuit model is shown below:

![Circuit Schematic](Images/شماتیک%20مدار.png)

---

# Simulation Results

## Step Response

![Step Response](Images/پاسخ%20پله.png)


## Zero Input Response

![Zero Input Response](Images/پاسخ%20ورودی%20صفر.png)


## Impulse Response

![Impulse Response](Images/پاسخ%20ضربه.png)


## Sinusoidal Output Voltage

![Sinusoidal Output Voltage](Images/ولتاژ%20خروجی%20سینوسی.png)


## Sinusoidal Input Current

![Sinusoidal Input Current](Images/جریان%20ورودی%20سینوسی.png)


## Steady State Sinusoidal Response

![Steady State Sinusoidal Response](Images/حالت%20دائمی%20سینوسی.png)


## Input Impedance Analysis

![Input Impedance Analysis](Images/امپدانس%20ورودی.png)


## Capacitor C1 Power Analysis

![Capacitor Power Analysis](Images/توان%20بار%20(خازن%20C1).png)

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
│   ├── شماتیک مدار.png
│   ├── پاسخ پله.png
│   ├── پاسخ ورودی صفر.png
│   ├── پاسخ ضربه.png
│   ├── ولتاژ خروجی سینوسی.png
│   ├── جریان ورودی سینوسی.png
│   ├── حالت دائمی سینوسی.png
│   ├── امپدانس ورودی.png
│   └── توان بار (خازن C1).png
│
├── LTspice
│   ├── OpAmp_Differential_Amplifier.asc
│   └── Simulation Files
│
├── Presentation
│   ├── پروژه مدار های الکتریکی (1).pdf
│   └── پروژه مدار های الکتریکی (1).pptx
│
└── README.md
```

---

# Files Description

## LTspice Folder

Contains the circuit simulation files:

- `.asc` schematic file
- LTspice simulation model


## Documentation Folder

Contains:

- Complete project report
- Technical explanations
- Simulation discussion


## Presentation Folder

Contains project presentation files:

- PDF format
- PowerPoint format


## Images Folder

Contains all simulation graphs and obtained results.

---

# Project Report

The complete technical report includes:

- Circuit design explanation
- Simulation methodology
- Mathematical analysis
- Obtained results
- Conclusions

Available at:

```
Documentation/Project_Report.pdf
```

---

# Conclusion

This project demonstrates the analysis and simulation of an operational amplifier differential amplifier system using LTspice.

Different simulation approaches were performed to evaluate circuit behavior in time domain, frequency-related behavior, impedance characteristics, and power response.

The results provide a complete understanding of the electrical performance and dynamic characteristics of the designed amplifier system.

---

# Author

**Arghavan Memari**

Electrical Engineering Project

---

# License

This project is intended for educational and academic purposes.
