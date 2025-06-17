# RISC-V Component Verification using SystemVerilog and UVM

## Overview

This repository contains modular testbenches and a reusable verification environment for key components of a RISC-V processor. The verification is implemented using SystemVerilog and follows UVM (Universal Verification Methodology) principles to ensure scalability, reusability, and coverage-driven testing.

## Verified Components

- ALU (Arithmetic Logic Unit)
- ALU Control Unit
- Program Counter
- Forwarding Unit
- Pipeline Registers (IF/ID, ID/EX, EX/MEM, MEM/WB)

## Features

- Modular SystemVerilog testbenches for each component
- UVM-based reusable verification framework
- Coverage-driven and constraint-random test scenarios
- Unified top-level testbench for batch execution
- Task-based control for clean simulation flow
- Debug-friendly waveform (.vcd) dumping

## Directory Structure

