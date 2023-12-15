# Simulation Model for Processing and Distribution of Products using Tecnomatrix

## Project Overview

This project involves the creation of a simulation model to optimize the processing and distribution of two products, "a" and "b," within a factory using Tecnomatrix software. The simulation includes detailed processes from the arrival of preloaded boxes to the departure of processed products, considering various processing machines, buffers, transporters, and storage areas.

## Simulation Scenario
### Arrival of Products
- Two products, "a" and "b," arrive in preloaded boxes (box 1 and box 2) every 9 minutes.
- Box capacities: Box 1 (10 units), Box 2 (8 units).
- Boxes are unboxed at positions 10m and 15m on Line 1.
### Processing Machines
- Product "a" is processed at Machine 1 and Machine 2.
- Product "b" is processed at Machine 3 and Machine 4.
- Processing times:
- Product "a": Machine 1 and Machine 2 (2 minutes each).
- Product "b": Machine 3 and Machine 4 (90 seconds each).
### Product Distribution
- Processed "a" and "b" are transferred to Line 2.
- Distribution to Line 3 and Line 4:
- Product "a" at Line 3 (Buffer p5, p6).
- Product "b" at Line 4 (Buffer p7, p8).
### Further Processing
- Products at Line 3 move to Buffer p6 and then to position 14m.
- Products at Line 4 move to Buffer p8 and then to position 14m.
### Additional Processing Machines
- Further processing of Product "a" at Machine 5 and Machine 6.
- Further processing of Product "b" at Machine 7 and Machine 8.
- Processing times:
- Product "a": Machine 5 and Machine 6 (90 seconds each, with a defect rate of 20%).
- Product "b": Machine 7 and Machine 8 (75 seconds each, with a defect rate of 25%).
### Defect Products
- Defect products from Machine 5 and Machine 7 are sent to Buffer p11.
- Transporter moves defect products from Buffer p11 to Buffer p4.
### Transportation and Storage
- Transporters: Three tracks with Transporter 1&2 (capacity: 50, speed: 0.90 m/s) and Transporter 3 (capacity: 10, speed: 0.90 m/s).
- Buffer capacities: p1 & p2 (50 units), others (8 units).
- Defect products at Buffer p4 are manually carried to Storage 2.

# Simulation of the Project
<p align="center">
  <img src="simulation of model.gif">
</p>

## System Requirements

- Tecnomatrix Software

## Usage

1. Clone this repository.
2. Open Tecnomatrix software.
3. Load the provided simulation model file (`simulation_model_warehouse.spp`).
4. Configure simulation parameters based on project specifications.
5. Run the simulation for 8 hours.

## Codes Used
- [List of suitable codes from the Tecnomatrix software documentation]
## Contributors
- Md Monjur Morhsed Tanjil

