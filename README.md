Overview

This repository contains a 32-bit MIPS processor implemented in Verilog HDL, designed to execute a subset of MIPS32 instructions. The processor supports a single-cycle architecture, providing a clear and practical understanding of fundamental processor design principles, including pipelining, hazard management, and control logic.

Features

Instruction Set: Supports a subset of MIPS32 instructions:

Arithmetic: add, sub

Logic: and, or

Load/Store: lw, sw

Branch: beq

Jump: j, jal, jr

Architecture:

32-bit data path

32 general-purpose registers

Single-cycle execution model

Simulation:

Testbenches included for simulation in ModelSim or Vivado

Example assembly programs to demonstrate functionality

Getting Started
Prerequisites

To run simulations or synthesize the design, you will need:

Verilog HDL-compatible simulator (e.g., ModelSim, Vivado)

Testbench files (included in this repository)

Running Simulations

Clone the repository:

git clone https://github.com/Dheeraj-75/MIPS32_processor_using_verilog.git
cd MIPS32_processor_using_verilog


Compile the Verilog source files:

vcom *.v


Run the simulation:

vsim work.mips_processor


Load the testbench and observe the results in the waveform viewer.

Directory Structure

src/ : Verilog source files for the processor

tb/ : Testbench files for simulation

docs/ : Documentation and design notes

scripts/ : Utility scripts for automation (if any)

Documentation

Detailed information on the processor design is available in the docs/ directory, including:

Block diagrams

Control and data path explanations

Instruction decoding logic

Timing diagrams
