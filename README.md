# 1x8 Demultiplexer using Verilog

## Objective
To design and simulate a 1x8 Demultiplexer using Verilog HDL.

## Description
A 1x8 Demultiplexer routes a single input signal to one of eight output lines based on three select lines (S2, S1, S0). Only the selected output follows the input, while all other outputs remain LOW.

## Truth Table

| S2 | S1 | S0 | Active Output |
|----|----|----|---------------|
| 0  | 0  | 0  | Y0 = I |
| 0  | 0  | 1  | Y1 = I |
| 0  | 1  | 0  | Y2 = I |
| 0  | 1  | 1  | Y3 = I |
| 1  | 0  | 0  | Y4 = I |
| 1  | 0  | 1  | Y5 = I |
| 1  | 1  | 0  | Y6 = I |
| 1  | 1  | 1  | Y7 = I |

## Files
1. demux1x8.v      - Verilog design code
2. demux1x8_tb.v   - Testbench
3. README.md       - Project documentation

## Software Required
- Xilinx Vivado
- ModelSim
- Icarus Verilog
- GTKWave (optional)

## How to Run
1. Compile demux1x8.v and demux1x8_tb.v.
2. Run the simulation.
3. Observe the waveform and verify the outputs.

## Expected Result
The input signal should appear only at the selected output according to the select lines, while all other outputs remain LOW.