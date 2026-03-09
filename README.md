# Ex No: 04 - Design & Implementation of 6T SRAM Cell Using Cadence EDA Tools

## Aim
The aim is to design and implement a 6T SRAM (Static Random-Access Memory) cell using Cadence EDA tools and verify its functionality through transient analysis simulation.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (45nm node)  

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure:
### 1. Launch Cadence Virtuoso Environment:
   - Open the Cadence Virtuoso tool and set up the working library.
   - Create a new schematic cell view for the 6T SRAM cell design.

### 2. Schematic Design:
   - Select NMOS and PMOS transistors from the library.
   - Construct the 6T SRAM cell with two cross-coupled inverters and access transistors.
   - Connect the wordline (WL), bitlines (BL, BLB), and power supply connections.

### 3. Simulation:
   - Check the design for errors and proceed with simulation.
   - Launch the Analog Design Environment (ADE).
   - Perform transient analysis to verify read and write operations.
   - Set up input stimulus and analyze the output waveform.

## Circuit Diagram

<img width="649" height="343" alt="image" src="https://github.com/user-attachments/assets/95583f2a-baf5-48d1-9905-e6791a3b82d5" />




## 6T SRAM Truth Table

![Screenshot 2025-03-24 123041](https://github.com/user-attachments/assets/29a8a036-d65d-4a25-ba18-3f1f0e358576)


## Schematic Diagram

#### 1. Schematic of 6T SRAM Cell:

   ![image](https://github.com/user-attachments/assets/2273733f-5e94-415a-9971-793c64816a0d)
   <img width="777" height="252" alt="image" src="https://github.com/user-attachments/assets/8916d270-20fe-45ac-a7c5-3eecb1767193" />






## Output
#### 1. Transient Analysis Output:

   
   ![WhatsApp Image 2026-02-20 at 10 33 02 AM](https://github.com/user-attachments/assets/a20e16d9-12b6-4f2e-a8a7-7ce19dbab0e3)


   ![122333](https://github.com/user-attachments/assets/355bd1d2-8dc1-45d9-ba74-77739f5de266)





## Results:
1. Successfully designed the 6T SRAM cell schematic using Cadence EDA tools.
2. Performed transient analysis, verifying the read and write operations of the SRAM cell.
3. Observed correct switching behavior in response to control signals.


