# VHDL-REPOSITRY
# FPGA OLED Accelerometer Display 📟⚡

FPGA-based embedded system designed to display real-time accelerometer data on a Pmod OLED screen using VHDL.

This project focuses on digital system design, hardware description, signal processing and FPGA-based peripheral interfacing.

---

# 🚀 Project Overview

The objective of this project was to design a digital architecture capable of:
- Reading acceleration values from 3 axes (X, Y, Z)
- Processing and converting binary data into ASCII characters
- Displaying formatted acceleration data on a Pmod OLED display
- Managing communication and synchronization between FPGA logic and the OLED peripheral

The entire system was developed in **VHDL** using combinational and sequential digital logic principles.

---

# 🛠️ Technologies Used

![VHDL](https://img.shields.io/badge/VHDL-543978?style=for-the-badge&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-FFB13B?style=for-the-badge)
![Vivado](https://img.shields.io/badge/Vivado-A00000?style=for-the-badge)
![QuestaSim](https://img.shields.io/badge/QuestaSim-003B6F?style=for-the-badge)

---

# ⚙️ System Features

✅ Real-time acceleration display  
✅ X / Y / Z axis selection  
✅ Binary-to-ASCII conversion  
✅ OLED peripheral interfacing  
✅ Digital signal routing using multiplexers  
✅ FPGA hardware implementation  
✅ Functional logic simulation  

---

# 🧠 What I Implemented

## 📌 Data Selection Logic

Implemented multiplexing logic to dynamically select:
- X-axis acceleration
- Y-axis acceleration
- Z-axis acceleration

depending on the current display line.

---

## 📌 Binary to ASCII Conversion

Designed conversion logic allowing FPGA acceleration values to be displayed as readable characters on the OLED screen.

Implemented:
- Numeric detection
- ASCII translation
- Character formatting

---

## 📌 Digital Logic Architecture

Developed several digital modules using:
- Combinational logic
- Conditional processing
- Signal routing
- Address decoding

including:
- Character detection
- Output multiplexing
- Line and character management

---

## 📌 OLED Display Interfacing

Managed communication signals for the Pmod OLED display:
- SPI interface signals
- Data/command control
- Display synchronization
- Character output management

---

# 📚 What I Learned

This project allowed me to strengthen my understanding of:

## FPGA & Digital Design
- Hardware description using VHDL
- Combinational vs sequential logic
- Signal synchronization
- FPGA architecture organization

## Embedded Hardware Communication
- OLED peripheral interfacing
- SPI communication principles
- Real-time data display systems

## Digital Data Processing
- Binary data manipulation
- ASCII encoding
- Multiplexer implementation
- Address decoding logic

## Engineering Workflow
- Hardware simulation
- Functional verification
- Debugging digital architectures
- Modular hardware design

---

# 🔬 Development Steps

## 1️⃣ Architecture Definition
- Defined FPGA inputs/outputs
- Designed OLED communication structure
- Planned signal routing architecture

## 2️⃣ VHDL Module Design
Implemented:
- Multiplexers
- Comparators
- ASCII conversion logic
- Detection modules
- Output routing logic

## 3️⃣ Simulation & Validation
- Functional simulations
- Timing verification
- Signal integrity validation
- Debugging architecture behavior

## 4️⃣ Hardware Integration
- FPGA synthesis
- OLED interfacing
- Real-time display testing

---

# 🧩 Key Concepts Used

- VHDL
- FPGA Design
- Combinational Logic
- Sequential Logic
- Multiplexers
- Signal Routing
- SPI Communication
- ASCII Encoding
- Hardware Simulation
- Embedded Display Systems

---

# 🎯 Project Goal

This project was designed to explore how FPGA architectures can process sensor data and directly control embedded display peripherals in real time.

It also provided hands-on experience with:
- Digital hardware design
- Peripheral communication
- Hardware/software abstraction
- FPGA-based embedded systems

---
