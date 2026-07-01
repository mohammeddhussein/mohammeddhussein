<div align="center">

# Hi, I'm Mohammed Hussein 👋

### ASIC / RTL Design Engineer &nbsp;|&nbsp; SoC Integration &nbsp;

**Building the bridge between silicon and software**

<!-- EDIT: keep, edit, or remove these badges -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohammedhusseinfahim)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:fahimm719@gmail.com)
[![Profile Views](https://komarev.com/ghpvc/?username=mohammeddhussein&style=flat&color=blue)](https://github.com/mohammeddhussein)

</div>

---

## About Me

I'm a Computer Engineering student and hardware design engineer focused on **RISC-V SoC integration** and **custom hardware accelerators**. My graduation project, **RISCyLUT**, involves integrating a custom **LUT-based Deep Learning Accelerator (LUT-DLA)** into a RISC-V System-on-Chip, covering the full stack from architecture and RTL design to driver development and ASIC synthesis.

**What I do:**
- Design and integrate SoC, with the suitable usage of interconnects (AHB/APB/AXI).
- Write HAL-style C drivers and verify hardware/software interaction via waveform-level debugging
- Take designs from RTL through gate-level synthesis using industry-standard EDA flows
- Build a suitable verification environment for designs (Module/Class/UVM-based).

**Engineering philosophy:**
I care about understanding *every* layer of the stack, starting from C code, to instruction set semantics, then down to register-transfer logic and physical gates. I'd rather spend an extra hour reading a waveform than guess at a fix: correctness, traceability, and clear documentation matter to me as much as a working design.

**Current focus:**
SoC Integration and exploring Digital Verification world.

**Career goals:**
I'm looking to grow into a full-time role in **RTL design, ASIC/Digital IC design, SoC integration, or hardware accelerator architecture**, ideally at a company building next-generation silicon for compute or AI.


---

## Technical Expertise

<table>
<tr>
<td valign="top" width="50%">

### RTL Design
- Parameterized, synthesizable Verilog / SystemVerilog
- FSM design
- Memory-mapped register file design
- Custom peripheral design (APB/AXI-attached)

### ASIC Physical Design
- Pre-place-and-route synthesis flows
- Gate-level netlist generation & timing reports
- Standard-cell technology library usage (e.g. SAED32)
- Synthesis constraint authoring
- TCL scripts writing

### Design for Test (DFT)
- Scan-friendly RTL coding practices
- Testbench-driven design validation

### Digital Verification
- Module-based testbench
- Class-based, OOP testbench environment
- Waveform-based debug (QuestaSim)

</td>
<td valign="top" width="50%">

### SoC Design
- CPU architecture concepts (Pipelining stages, Branch prediction, Controlling hazards)
- RISC-V SoC integration (PulpISSimo / RI5CY)
- AMBA protocol integration: APB, AHB, AXI4
- Bus matrix and interconnect architecture
- Memory subsystem design (HBM)

### Embedded Systems
- HAL-style C driver development for custom peripherals
- Cross-compilation toolchains for RISC-V targets

### FPGA
- RTL prototyping and simulation-based validation

### AI Hardware Acceleration
- LUT-based Deep Learning Accelerator (LUT-DLA) integration
- Control/data-plane separation for accelerator interfaces
- Accelerator-to-core communication protocol design

</td>
</tr>
</table>

---

## Tech Stack

**HDLs**

![Verilog](https://img.shields.io/badge/Verilog-CC0000?style=flat)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-9B1B1B?style=flat)

**Programming Languages**

![C](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)

**EDA Tools**

![QuestaSim](https://img.shields.io/badge/QuestaSim-1E3A8A?style=flat)
![Synopsys Design Compiler](https://img.shields.io/badge/Synopsys%20Design%20Compiler-0072CE?style=flat)

**Verification**

![UVM Concepts](https://img.shields.io/badge/UVM%20Methodology-5D3FD3?style=flat)
![Assertions](https://img.shields.io/badge/SVA-5D3FD3?style=flat)

**Scripting**

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![TCL](https://img.shields.io/badge/Tcl-3A5FCD?style=flat)
![Makefile](https://img.shields.io/badge/Make-A42E2B?style=flat&logo=gnu&logoColor=white)

**Operating Systems**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![WSL](https://img.shields.io/badge/WSL-0078D4?style=flat&logo=windows&logoColor=white)

**Version Control**

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)

---

## Featured Projects

<!-- EDIT: replace repo-name with your actual repository names; GitHub will auto-populate stars/language if you use the repo card format below -->

### [RTL-to-GDS Implementation of Low-Power Configurable Multi-Clock Digital System](https://github.com/mohammeddhussein/RTL-to-GDS-Implementation-of-Low-Power-Configurable-Multi-Clock-Digital-System)
A system that's responsible for receiving commands through UART receiver to do different system functions as register file reading/writing or doing some processing using ALU block and send result to UART transmitter through asynchronous FIFO for handling different clock rates and avoid data loss.
**Stack:** SystemVerilog, C, QuestaSim, Synopsys DC, Cadence SoC Encounter, Formality

### [Single-Cycle MIPS CPU](https://github.com/mohammeddhussein/Single-Cycle-MIPS)
A from-scratch single-cycle MIPS CPU implementation in SystemVerilog, built to understand the full hardware/software stack from ISA design down to datapath and control logic.
**Stack:** SystemVerilog

### [SPI Slave with Single Port RAM](https://github.com/mohammeddhussein/SPI-Slave-with-Single-Port_RAM)
A synthesizable SPI slave peripheral with a self-checking testbench and loopback stimulus generation.
**Stack:** SystemVerilog

---

<!--
## GitHub Statistics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mohammeddhussein&show_icons=true&theme=default&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mohammeddhussein&layout=compact&hide_border=true&theme=default)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=mohammeddhussein&hide_border=true&theme=default)

</div>

---

## Contribution Graph

<div align="center">

![Contribution Graph](https://github-readme-activity-graph.vercel.app/graph?username=mohammeddhussein&theme=minimal&hide_border=true)

</div>

---
-->
## Connect With Me

<!-- EDIT: fill in real links -->
<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mohammedhusseinfahim)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fahimm719@gmail.com)

</div>

---



<div align="center">
<sub>Last updated: <!-- EDIT: month/year -->July 2026</sub>
</div>
