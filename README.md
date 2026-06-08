# FPGA-Based Elevator Controller Using Verilog HDL

## Overview

This project presents the design and simulation of a 4-floor Elevator Controller using Verilog HDL. The controller is implemented using Finite State Machine (FSM) concepts to manage elevator movement between floors. The system accepts floor requests, determines the direction of movement, updates the current floor, and controls door operations upon reaching the destination.

The project demonstrates key FPGA and digital logic design concepts including state machines, sequential circuits, simulation, and waveform verification.

---

## Objectives

* Design an Elevator Controller using Verilog HDL.
* Implement FSM-based control logic.
* Simulate elevator movement between floors.
* Verify functionality through simulation output.
* Analyze signal behavior using waveform analysis.

---

## Features

* 4-Floor Elevator System
* FSM-Based Design
* Upward Floor Movement
* Downward Floor Movement
* Door Open State
* Verilog HDL Implementation
* Simulation and Verification
* Waveform Analysis using EPWave

---

## FSM States

| State     | Description                     |
| --------- | ------------------------------- |
| IDLE      | Waits for a floor request       |
| MOVE_UP   | Elevator moves upward           |
| MOVE_DOWN | Elevator moves downward         |
| DOOR_OPEN | Door opens at destination floor |

---

## Tools and Technologies

* Verilog HDL
* FPGA Design Concepts
* EDA Playground
* Icarus Verilog
* EPWave

---

## Project Structure

FPGA-Elevator-Controller-Verilog/

├── design.sv

├── testbench.sv

├── README.md

├── Project_Report.docx

└── Screenshots/

    ├── Design_Code.png

    ├── Simulation_Output.png

    └── Waveform_Output.png

---

## Working Principle

1. The elevator starts in the IDLE state.
2. A user requests a floor.
3. The controller compares the requested floor with the current floor.
4. If the requested floor is higher, the elevator enters MOVE_UP state.
5. If the requested floor is lower, the elevator enters MOVE_DOWN state.
6. Once the destination floor is reached, the controller enters DOOR_OPEN state.
7. After door operation, the controller returns to IDLE.

---

## Results

The simulation results demonstrate successful floor transitions and correct FSM state changes. Waveform verification confirms proper operation of all signals including clock, reset, floor request, current floor, and state transitions.

---

## Applications

* Elevator Control Systems
* Digital Logic Design Projects
* FPGA Learning and Training
* Industrial Automation Systems
* FSM-Based Embedded Controllers

---

## Future Scope

* Support for additional floors
* Multiple request handling
* Priority-based scheduling
* Emergency stop functionality
* FPGA hardware implementation

---

## Conclusion

The FPGA-Based Elevator Controller was successfully designed and verified using Verilog HDL. The project demonstrates the practical implementation of FSM concepts and digital system design techniques. Simulation and waveform analysis validate the correct behavior of the controller and provide a foundation for more advanced FPGA-based control systems.

---

## Author Details

**Name:** Jenifer J

**Intern ID:** CITS2086

**Project:** FPGA-Based Elevator Controller Using Verilog HDL

**Technology:** Verilog HDL, FPGA Design

**Platform:** EDA Playground

**Verification Tool:** EPWave
