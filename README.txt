# Wrist Force Control Project

This repository contains the Simulink models, MATLAB scripts, and configuration files used for developing a force-controlled wrist mechanism using Maxon motors and Simulink Real-Time (SLRT).

## 🛠 Project Structure


 Build artifacts (e.g. code generation output from SLRT) are excluded via `.gitignore`.

---

## Features

- Real-time torque control using Maxon EPOS4 over EtherCAT
- CST (Cyclic Synchronous Torque) mode integration
- Analog encoder offset compensation
- Designed for wrist-mounted robotic actuation

---

## Requirements

- MATLAB R2020b or before
- Simulink Real-Time Toolbox
- Maxon EPOS4 motor drivers
- TwinCAT XML configuration (for EtherCAT import)
- If you use MATLAB Simuulik 2020 and before use Beckhoff or Speedgoat Target Machine(for real-time testing)

---

##Usage

1. Launch MATLAB and open the main model:
   ```matlab
   open('Wrist_Force_Control.slx')