# T-Intersection Traffic Controller: Verilog Design and Simulation

## Project Overview
This project presents a Verilog-based design and simulation of a traffic controller for a T-intersection. The controller optimizes traffic flow and enhances pedestrian safety by managing vehicle movement from three sides. It includes a two-layer control system for one direction, integrating a pedestrian push button to halt traffic, enabling safe pedestrian crossings.

## Objectives
- **Traffic Management:** Efficiently direct vehicle flow at a T-intersection using a sequence of traffic modes.
- **Pedestrian Safety:** Implement a pedestrian push button to safely interrupt vehicle movement when needed.
- **Verilog Simulation:** Simulate the controller to validate its functionality in real-time conditions.

## System Components
- **Verilog Program:** Core code implementing the traffic controller logic.
- **Traffic Modes:** Defined sequence for each traffic light to optimize flow.
- **Pedestrian Control:** Mechanism to allow safe crossings by halting all traffic.

## Modes and Operation
The traffic controller operates in a sequence of modes (Mode 1, Mode 2, Mode 3), with a special Mode 0 activated by the pedestrian push button, halting traffic for safe crossings.

## Verilog Implementation
- **Traffic Controller Module:** Implements the traffic signal logic and controls vehicle and pedestrian flows.
- **TestBenches:** Simulates different scenarios:
  - No pedestrian crossing.
  - Pedestrian button pressed once.
  - Pedestrian button pressed twice.
