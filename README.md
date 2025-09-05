# Basic_ALU_Project
A simple 4-bit Arithmetic Logic Unit (ALU) designed in Verilog. The ALU performs basic arithmetic and logical operations including addition, subtraction, AND, OR, and XOR. The project includes a Verilog testbench with simulation results to verify functionality. Built to strengthen fundamentals.

**Features**
- 4-bit input operands (`A`, `B`)
- Control signal (`op_code`) to select the operation
- Supported operations:
  - Addition (`A + B`)
  - Subtraction (`A - B`)
  - Bitwise AND (`A & B`)
  - Bitwise OR (`A | B`)
  - Bitwise XOR (`A ^ B`)
- Includes a Verilog **testbench** for simulation and verification
- Simulation waveforms provided

**Project Structure**
Basic_ALU_Project/
├── src/
│ └── ALU.v # Verilog implementation of the ALU
├── testbench/
│ └── ALU_tb.v # Testbench for simulation
├── simulation_results/
│ └── waveform.png # Example waveform screenshot
└── README.md

**Tools & Technologies**
 - Verilog HDL for design
 - Vivado for simulation
 - GitHub for version control  and project sharing
