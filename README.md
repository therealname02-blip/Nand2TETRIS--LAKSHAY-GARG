# Nand2Tetris – Projects 1, 2 & 3

## Project Description

This repository contains Hardware Description Language (HDL) implementations of digital logic circuits developed as part of the **Nand2Tetris (The Elements of Computing Systems)** course.

The projects demonstrate how a computer's fundamental hardware components are built using basic logic gates, arithmetic circuits, and memory units.

## Project 1: Boolean Logic

Project 1 focuses on designing basic logic gates and building more complex circuits using NAND gates.

### Chips Implemented

- **Not** – Inverts a binary input.
- **And** – Performs logical AND operation.
- **Or** – Performs logical OR operation.
- **Xor** – Performs exclusive OR operation.
- **Mux** – Selects one of two inputs.
- **DMux** – Routes an input to one of two outputs.
- **Not16** – Performs bitwise NOT on 16-bit input.
- **And16** – Performs bitwise AND on 16-bit inputs.
- **Or16** – Performs bitwise OR on 16-bit inputs.
- **Mux16** – Selects between two 16-bit inputs.
- **Or8Way** – Performs OR operation on 8 input bits.
- **Mux4Way16** – Selects one of four 16-bit inputs.
- **Mux8Way16** – Selects one of eight 16-bit inputs.
- **DMux4Way** – Routes input to one of four outputs.
- **DMux8Way** – Routes input to one of eight outputs.

## Project 2: Boolean Arithmetic

Project 2 focuses on building arithmetic circuits and the Arithmetic Logic Unit (ALU).

### Chips Implemented

- **HalfAdder** – Adds two 1-bit binary numbers.
- **FullAdder** – Adds three 1-bit binary inputs.
- **Add16** – Adds two 16-bit binary numbers.
- **Inc16** – Increments a 16-bit number by one.
- **ALU** – Performs arithmetic and logical operations.

### ALU Features

The ALU supports addition, bitwise AND, input negation, output negation, and zeroing inputs.

It uses six control bits: `zx`, `nx`, `zy`, `ny`, `f`, and `no`.

It also produces two status outputs:
- `zr` – Indicates whether the result is zero.
- `ng` – Indicates whether the result is negative.

## Project 3: Sequential Logic

Project 3 focuses on memory circuits, registers, and sequential logic.

### Chips Implemented

- **Bit** – Stores a single bit.
- **Register** – Stores a 16-bit value.
- **RAM8** – Stores 8 words of 16 bits.
- **RAM64** – Stores 64 words of 16 bits.
- **RAM512** – Stores 512 words of 16 bits.
- **RAM4K** – Stores 4096 words of 16 bits.
- **RAM16K** – Stores 16384 words of 16 bits.
- **PC (Program Counter)** – Maintains and updates the instruction address.

## Technologies Used

- Hardware Description Language (HDL)
- Nand2Tetris Hardware Simulator
- Boolean Algebra
- Digital Logic Design
- Computer Architecture

## How to Run the Projects

1. Download the Nand2Tetris software tools from the official website.
2. Open the Hardware Simulator.
3. Load the required `.hdl` chip file.
4. Load the corresponding `.tst` test script.
5. Run the simulation.
6. Compare the generated output with the expected `.cmp` file.

## Learning Outcomes

Through these projects, I learned:

- How to construct logic gates using NAND gates.
- How multiplexers and demultiplexers control data flow.
- How binary arithmetic operations are performed.
- How an ALU processes arithmetic and logical instructions.
- How registers and RAM store binary information.
- How sequential circuits maintain state.
- How a Program Counter controls instruction sequencing.

## Conclusion

Nand2Tetris Projects 1, 2, and 3 provide a strong foundation in digital logic design and computer architecture.

These projects demonstrate the process of building complex hardware components from simple Boolean gates, progressing from combinational logic to arithmetic processing and memory systems.

## References

**Nand2Tetris – The Elements of Computing Systems**

Official Website: https://www.nand2tetris.org/

Authors: Noam Nisan and Shimon Schocken
