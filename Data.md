# Analog Front-End (AFE) Design using LTspice

This repository contains a modular Analog Front-End (AFE) design developed and simulated using **LTspice**. The project includes various analog building blocks such as operational transconductance amplifiers (OTAs), sample-and-hold circuits, transmission gates, switches, and ADC interfaces.

## 📁 Project Structure
├── OTA_SingleEnded_Design # Single-ended OTA schematic and simulations
├── APS_CTIA # Active Pixel Sensor with CTIA structure
├── Sample_Hold_Circuit # Sample and Hold block
├── Transmission_Gates # Transmission gate designs
├── Differential_Pair # Differential amplifier and buffers
├── CMFB_Circuit # Common-mode feedback design
├── ADC_DS_CT_DIFF # Differential ADC driver block
├── SC_Amp_Diff # Switched-capacitor amplifier stage
├── Symbols # Custom LTspice symbols
└── Simulation_Results # .op/.raw simulation files


## 🔧 Features

- 📐 **Modular Design**: Built using reusable LTspice hierarchical blocks and custom symbols.
- 📈 **Gain and Stability Optimization**: Improved open-loop/closed-loop gain, phase margin, and bandwidth via compensation techniques.
- 🔍 **Simulation Driven**: Transient, AC, DC sweep, and parametric simulations for each stage.
- 🔁 **Common-Mode Feedback**: CMFB implemented for differential paths to maintain DC stability.
- 🔌 **Analog Blocks**: Includes OTA, CTIA, sample & hold, transmission gates, and a differential ADC driver.
- 🧪 **Custom Testbenches**: Each block has its own testbench setup to validate functionality and performance.

## 🧠 Design Goals

- Develop a front-end suitable for image sensor or signal acquisition systems.
- Ensure low-noise operation with high linearity and gain accuracy.
- Validate PVT robustness and proper phase margin across feedback loops.

## 📎 Tools Used

- LTspice 
- SPICE simulation
- Custom LTspice symbol creation
- 65nm_bulk.txt file
## 📌 Getting Started

1. Open `.asc` files in LTspice.
2. Use `.op` or `.raw` files to view simulation results.
3. Run AC, transient, or parametric simulations by modifying the simulation commands.
4. Use custom symbols (`.asy`) for hierarchy-enabled schematic blocks.


## 📜 License

This project is open for academic and personal use. If reused or modified, please give credit.

---

Saswat Padhy  
IIT Kharagpur
