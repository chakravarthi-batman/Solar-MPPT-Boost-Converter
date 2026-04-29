# Solar PV System with MPPT and Boost Converter

## 📌 Overview
This project models a solar photovoltaic (PV) system integrated with a boost converter and Maximum Power Point Tracking (MPPT) using the Perturb & Observe (P&O) algorithm in MATLAB/Simulink.

## ⚡ Features
- Solar PV modeling using diode characteristics
- Boost converter for voltage step-up
- PWM-based MOSFET switching
- MPPT using Perturb & Observe algorithm
- Efficient power extraction from solar panel

## 🧠 Working Principle
The solar panel generates power based on irradiance. The MPPT algorithm continuously adjusts the duty cycle of the boost converter to ensure operation at the maximum power point.

## 🔧 Components Used
- Solar PV model
- Inductor (5 mH)
- Capacitor (2200 µF)
- MOSFET switch
- Diode
- Load resistor
- Voltage & current sensors

## 📊 Results
- PV Power: ~70–110 W
- Output Power: ~60–90 W
- Efficiency: ~85–92%
- Stable MPPT tracking achieved

## 🚀 Applications
- Solar energy systems
- Renewable energy research
- Power electronics education

## 🛠 Tools Used
- MATLAB Simulink
- Simscape Electrical

## 📌 Future Improvements
- Adaptive MPPT algorithms
- Closed-loop voltage control
- Hardware implementation
