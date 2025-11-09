# 4-Bit ALU (Arithmetic Logic Unit) in Verilog

A simple, modular **4-bit Arithmetic Logic Unit (ALU)** implemented in **Verilog HDL** and simulated using **Xilinx Vivado**.  
This project demonstrates key digital design concepts such as combinational logic, arithmetic operations, and HDL simulation workflows used in FPGA design.

---

## Features

- 16 operation codes (`opcode`) supporting arithmetic and logic functions  
- Fully **combinational** (no clock required)  
- **Synthesizable** for FPGA targets  
- Includes **Vivado testbench** for functional simulation  
- Clean, well-documented Verilog structure suitable for academic or portfolio demonstration  

---

## Supported Operations

| Opcode | Operation Name     | Description                          | 
|:------:|:-------------------|:-------------------------------------|
| 0000   | OR Reduction       | `x[0] = |a`                          | 
| 0001   | AND Reduction      | `x[0] = &a`                          |
| 0010   | XOR Reduction      | `x[0] = ^a`                          |
| 0011   | AND                | `x = a & b`                          |
| 0100   | OR                 | `x = a | b`                          | 
| 0101   | XOR                | `x = a ^ b`                          | 
| 0110   | Greater Than       | `x[0] = (a > b)`                     | 
| 0111   | Less Than          | `x[0] = (a < b)`                     |
| 1000   | NOR Reduction      | `x[0] = ~|a`                         |
| 1001   | Equality           | `x[0] = (a == b)`                    |
| 1010   | Addition           | `{y[0], x} = a + b`                  | 
| 1011   | Subtraction        | `x = a - b`                          |
| 1100   | Multiplication     | `{y, x} = a * b`                     |
| 1101   | Shift Right        | `{y, x} = {4'b0, a} >> b`            |
| 1110   | Shift Left         | `{y, x} = {a, 4'b0} << b`            | 
| 1111   | NOT                | `x = ~a`                             |

---

## 📚 Tools & Technologies

- **HDL:** Verilog  
- **Simulation & Synthesis:** Xilinx Vivado  
- **Version Control:** GitHub  

