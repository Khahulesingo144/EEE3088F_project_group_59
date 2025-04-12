# EEE3088F_project_group_59

This is intended to be the repository used to track any changes made to the schematic that we will use for the project. Any and all changes will be made and committed with comments to note what was changed.

# EEE3088F 2025 Micro-Mouse Power Subsystem

## Overview
This repository contains all design files and documentation for the power subsystem of the Micro-Mouse project, as part of the EEE3088F 2025 course at the University of Cape Town. 

The power module is responsible for delivering regulated power to the entire micro-mouse system, supporting motor driving, USB-C power input, battery monitoring and charging, and high-side switching for external loads.

## Repository Structure


## Project Objectives
- Design and manufacture a power PCB that:
  - Powers 4 motors (2x 200mA and 2x 500mA brushed DC)
  - Charges a LiPo battery from a 9V USB-C input (with 200mA and ~600mA charge modes)
  - Integrates an INA219 sensor for battery voltage/current monitoring
  - Supplies 5V @ 1.5A and 3.3V @ 300mA regulated outputs
  - Supports dual high-side external load switching (1A each)
  - Includes ON/OFF switching (<30μA off-state draw, 2A on-state peak)
- Stay within the strict $70 budget for manufacturing and components
- Ensure physical compatibility with the provided micro-mouse motherboard

## Tools Used
- **KiCad** – Schematic capture and PCB layout
- **JLCPCB** – PCB manufacturing and assembly
- **Git** – Version control
- **LaTeX** – Report writing

## Key Files
- `production_files/EEE3088F_PowerModule_Gerbers.zip` – Final Gerber files for PCB manufacturing
- `production_files/BOM.csv` – Bill of Materials for JLCPCB
- `production_files/CPL.csv` – Pick and Place file for assembly
- `images/` – Includes screenshots of BOM upload and order verification for JLCPCB submission

## Contributors
- **Student 1**: Khahule Singo, Student Number: SNGKHA008
- **Student 2**: Otsile Diale, Student Number: DLXOTS001

Each student is responsible for distinct sections of the design and has submitted an individual report accordingly.

## License
This repository is intended for academic use only. Please do not reproduce or redistribute without permission.


