# AND-Gate-Physical-Design-using-OpenLane-and-Sky130-PDK
Implemented the complete RTL-to-GDSII Physical Design flow of an AND Gate using OpenLane, OpenROAD, Magic VLSI, and KLayout with the Sky130 PDK. Generated the final GDSII layout and analyzed the design using open-source ASIC design tools.

## Overview
This project demonstrates the complete RTL-to-GDSII Physical Design flow of an AND Gate using the OpenLane ASIC flow with the Sky130 PDK.

The design flow includes synthesis, floorplanning, placement, clock tree synthesis, routing, and final GDSII generation.

## Tools Used

- OpenLane
- OpenROAD
- Magic VLSI
- KLayout
- Sky130 PDK
- Docker
- Ubuntu Linux

## Design Flow

1. RTL Design
2. Synthesis
3. Floorplanning
4. Placement
5. Clock Tree Synthesis
6. Routing
7. DRC Checking
8. GDSII Generation
9. Layout Visualization

## Project Structure

```text
and_gate/
├── src/
├── config.json
├── runs/
├── results/
└── reports/

## Generated Outputs

- DEF File
- LEF File
- GDSII Layout
- Timing Reports
- Metrics Report

## Final Layout

The final GDSII layout was successfully generated and visualized using KLayout.

## Learning Outcomes

Through this project, I gained practical experience in:

- ASIC Physical Design Flow
- Open-source EDA tools
- Linux-based VLSI environment
- RTL-to-GDSII implementation
- Layout visualization and analysis

## Keywords

VLSI, OpenLane, OpenROAD, ASIC Design, Sky130, Physical Design, KLayout, Magic VLSI, RTL-to-GDSII
