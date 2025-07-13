# ALU-implementation-and-verification
ALU implementation and verification using Cadence Virtuoso and Verilog HDL

# Overview
This project showcases a complete digital hardware design flow for an Arithmetic Logic Unit (ALU), covering both RTL and transistor-level design. The ALU was first written in Verilog HDL as a synthesizable RTL model, then re-implemented in Cadence Virtuoso using the GPDK090 (90nm) technology. Functional equivalence was verified through simulation and waveform comparison.

# Features
- Supports multiple ALU operations: ADD, SUB, AND, OR, XOR, NOT, etc.

- RTL implementation using Verilog HDL

- Transistor-level schematic design in Cadence Virtuoso using GPDK090

- Verification through testbenches and waveform comparison across both implementations

# Tools & Technologies
- Verilog HDL – RTL design and simulation

- Cadence Virtuoso – Transistor-level schematic design

- GPDK090 – 90nm Generic Process Design Kit

- Simulation Tools – Cadence Spectre / Verilog simulator (ModelSim/VCS)

- GTKWave / Virtuoso Waveform Viewer – For result analysis

# Verification Methodology
- Created a testbench for the Verilog ALU to generate input stimuli and observe outputs

- Simulated both the Verilog RTL and Cadence schematic using equivalent input sets

- Compared output waveforms to ensure functional equivalence of both implementations

# Use Cases
- Educational demo of digital design from HDL to transistor level

- Practice with ASIC design tools and standard cell-level design using GPDK090

- Custom ALU development and verification in a typical digital backend workflow

