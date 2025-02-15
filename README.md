Overview
This project is a RISC-V CPU implemented in Logisim Evolution as part of the CS61C Computer Architecture course at UC Berkeley. The CPU follows the RISC-V ISA (RV32I) and is designed using basic logic gates, registers, and multiplexers.

Project Features
5-Stage Pipeline Design (Fetch, Decode, Execute, Memory, Writeback)
32-bit Register File with Read/Write capabilities
ALU supporting RISC-V arithmetic and logic operations
Branch Comparator for conditional execution
Instruction and Data Memory (IMEM & DMEM)
Control Logic Unit to handle instruction execution flow
File Structure
cpu.circ - Main CPU circuit
alu.circ - Arithmetic Logic Unit
regfile.circ - Register File
branch-comp.circ - Branch Comparator
control-logic.circ - Control Logic Unit
imem.circ - Instruction Memory
dmem.circ - Data Memory
How to Run
Open Logisim Evolution (java -jar logisim-evolution-x.x.x-all.jar).
Load cpu.circ as the main circuit.
Run the simulation to test RISC-V programs.
Demo
Here’s a screenshot of the CPU design in Logisim Evolution:
![CPU Design](https://github.com/Dao1213/RISC-V_logism/blob/main/Screenshot%20(1340).png)
