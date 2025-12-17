# Logisim Simple ALU
## 8-Bit Arithmetic Logic Unit Design Project for Computer Architecture class

This repository contains a complete 8-bit ALU (Arithmetic Logic Unit) designed and implemented in Logisim as part of a Computer Architecture course project.

## 📋 Project Overview

This project involves designing and building a simple CPU through four phases:
1. **Phase One**: Design and build an 8-bit ALU with 14 operations
2. **Phase Two**: Create instruction set architecture with multiplexer
3. **Phase Three**: Implement control unit and operand registers
4. **Phase Four**: Write assembly language programs

## 🔧 Features

### ALU Operations (14 Total)

#### Required Operations (9):
- **ADD** (0000) - Arithmetic addition
- **INC** (0001) - Increment by 1
- **DEC** (0010) - Decrement by 1
- **CMP** (0011) - Comparison (outputs: Equal, LessThan, GreaterThan)
- **NOT** (0100) - Bitwise NOT
- **AND** (0101) - Bitwise AND
- **OR** (0110) - Bitwise OR
- **SHR** (0111) - Shift Right (logical)
- **SHL** (1000) - Shift Left (logical)

#### Additional Operations (5):
- **XOR** (1001) - Bitwise XOR
- **SUB** (1010) - Subtraction
- **NAND** (1011) - Bitwise NAND
- **NOR** (1100) - Bitwise NOR
- **PASS A** (1101) - Pass through operand A
