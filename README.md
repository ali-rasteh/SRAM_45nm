# SRAM 6T Simulation Project

This repository contains the code for my MSc project on SRAM 6T simulation using HSpice. The project focuses on mitigating the impact of leakage current on SRAM operating speed in near-threshold voltage regions and high-temperature environments.

## Project Abstract
SRAM is widely used in platforms like cache memory in microcontrollers and different types of processors and is preferred for applications requiring high-speed or static memory circuits. This thesis proposes a novel method to mitigate the impact of leakage current on SRAM operating speed in near-threshold voltage regions and high-temperature environments. The approach uses SRAM columns with leakage current compensation circuits to achieve the desired performance.

## Keywords
- SRAM
- Leakage Current
- Process Variations
- Leakage Current Compensation
- Code Description

The main code file in this repository is SRAM_LVR_simulation.sp, which includes the following sections:

- Library Configurations: Settings for optimal accuracy, convergence, and runtime.
- Parameter Definitions: Defines various parameters such as voltage levels, clock periods, and leakage currents.
- Subcircuits: Definitions of the SRAM 6T cell and other components like sense amplifiers, write drivers, and logic gates.
- Main Circuit: Configuration of the main SRAM column, including voltage sources and timing circuits.
- Leakage Compensation Circuit: Circuits designed to compensate for leakage currents in the SRAM cells.
- Output Settings: Measurement and output settings for the simulation results.

You can find the complete code and configuration in the SRAM_LVR_simulation.sp file.

## Repository Contents
- README.md: This README file.
- SRAM_LVR_simulation.sp: The main simulation code for the SRAM 6T project.

## Usage

To run the simulations, you need HSpice installed on your system. Load the SRAM_LVR_simulation.sp file into HSpice and run the simulation to observe the results.
