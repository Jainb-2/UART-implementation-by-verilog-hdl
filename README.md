# UART Implementation in Verilog

This repository contains a simple implementation of a Universal Asynchronous Receiver/Transmitter (UART) written in Verilog HDL. It is designed to be easily integrated with FPGA projects and has been tested on the Xilinx Artix-7 FPGA using the Arty Development Board from Digilent.

## Overview

This UART implementation provides basic functionality for serial communication. It includes both transmitter and receiver modules and is suitable for educational purposes and as a peripheral in various FPGA projects. The design is tested with a 50MHz clock and can be adapted for higher speeds with proper pin buffering.

## Tools

- **[Icarus Verilog](http://iverilog.icarus.com/)**: Verilog simulation and synthesis tool.
- **[GTKWave](http://gtkwave.sourceforge.net/)**: Waveform viewer for simulation results.

To install the tools on Ubuntu, run:

```sh
$> sudo apt-get install iverilog gtkwave
```
##Simulation
To run the testbenches for the UART modules, use the provided Makefile:
