# Traffic Light Controller using Verilog

## Overview

This project implements a **finite-state traffic light controller** for a T-intersection using Verilog RTL.

The controller uses sequential state transitions to coordinate traffic signals across intersecting roads. Signal timing and state control are implemented to provide an organized sequence of traffic-light phases.

## Features

- Finite State Machine (FSM) based design
- Verilog RTL implementation
- Sequential state transitions
- Configurable signal timing
- Coordinated traffic-light control
- Verilog-based testbench
- RTL simulation and functional verification
- Xilinx Vivado design and simulation

## System Design

The controller can be represented as:

```text
              +-------------------+
              |   Traffic Inputs  |
              +---------+---------+
                        |
                        v
              +-------------------+
              |   FSM Controller  |
              |                   |
              | State Transition  |
              | Signal Timing     |
              +---------+---------+
                        |
                        v
              +-------------------+
              | Traffic Signals   |
              |                   |
              | Road A / Road B   |
              +-------------------+
