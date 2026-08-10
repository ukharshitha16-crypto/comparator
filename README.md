# 2-Bit Comparator Using Verilog HDL

## Overview

This project implements a 2-bit digital comparator using Verilog HDL. The comparator compares two 2-bit binary inputs and generates outputs indicating whether the first input is greater than, equal to, or less than the second input.

## Features

* Compares two 2-bit inputs
* Generates three outputs:

  * A_greater
  * A_equal
  * A_less
* Simple combinational logic design
* Verified using a Verilog testbench

## Files

* `comparator.v` – Comparator design module
* `comparator_tb.v` – Testbench file
* `simulation_results.png` – Simulation waveform screenshot

## Truth Table

| Condition | Output        |
| --------- | ------------- |
| A > B     | A_greater = 1 |
| A = B     | A_equal = 1   |
| A < B     | A_less = 1    |

## Tools Used

* Verilog HDL
* Icarus Verilog
* ModelSim / GTKWave

## Simulation Steps

1. Compile the Verilog design and testbench.
2. Run the simulation.
3. Open the waveform viewer.
4. Verify the comparator outputs.

## Applications

* Arithmetic Logic Units (ALUs)
* Digital Signal Processing
* Microprocessors
* Embedded Systems
* Decision-Making Circuits

## Result

The comparator correctly identifies whether A is greater than, equal to, or less than B for all tested input combinations.

## Author

Akula Rajini Yadav

B.Tech – Electronics and Communication Engineering (ECE)
