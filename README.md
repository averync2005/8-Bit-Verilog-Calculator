# 8-Bit Verilog Calculator with BCD Display  
ECE 128 – Digital System Design  
Final Project – Fall 2025  
Avery Nudell-Cook & Colin Sawyer  

## Overview  
This project implements an 8-bit calculator on the Basys 3 FPGA board using Verilog.  
The calculator performs eight operations using two 4-bit operands:  

Arithmetic Operations  
• Addition  
• Subtraction  
• Multiplication  
• Division (quotient only)

Logical Operations  
• AND  
• OR  
• XOR  
• NOT (applied to operand A)

The computed result is converted from binary to BCD format and displayed on the Basys 3 seven-segment display using a multiplexed digit driver.  
This project integrates arithmetic modules, logical modules, a Binary-to-BCD converter, and a complete seven-segment display controller.

---

## Features  
• Fully modular Verilog design  
• Clean top-level Calculator module  
• Custom Binary-to-BCD converter using the double-dabble algorithm  
• Four-digit multiplexed seven-segment display driver  
• Intuitive, readable Verilog code  
• Complete testbench for simulation  
• Basys 3 constraints file included
