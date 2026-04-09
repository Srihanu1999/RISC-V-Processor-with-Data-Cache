# RISC-V Processor with Integrated Data Cache

## Overview
This project implements a 32-bit single-cycle RISC-V processor (RV32I) in Verilog with an integrated data cache. The design focuses on building a modular processor and extending it with basic cache support for data memory access. The complete system is verified using ModelSim.

## Features
- 32-bit RISC-V processor supporting RV32I instructions  
- Modular design including ALU, control unit, and memory modules  
- Direct-mapped data cache for handling memory access  
- Basic handling of cache hit and miss conditions  
- Processor waits when data is not immediately available from memory  
- Testbench included for functional verification  

## Simulation
The design was simulated using ModelSim. Functional correctness was verified by observing instruction execution and cache behavior under different memory access scenarios.

## Learnings
- Designed a RISC-V processor using Verilog  
- Understood basic cache concepts such as hit and miss  
- Gained experience in simulation and waveform analysis  
