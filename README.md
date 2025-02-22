# Hardware-in-the-Loop---LABVIEW
This project is developed to evaluate the performance of DC-DC converter in LABVIEW, including interactive design workbench, coding, and evaluation at the end. 
# Hardware-in-the-Loop (HiL) DUT Tester

## Project Overview
This repository contains the Hardware-in-the-Loop (HiL) test setup for validating the performance of a DC-DC converter (LM2596) under varying load conditions. The project involves LabVIEW-based data acquisition and control using the NI USB-6001 DAQ module.

## Features
- Real-time measurement of input voltage, input current, and power.
- Dynamic control of load resistors via digital signals.
- Efficiency calculation based on measured parameters.
- Automated testing and logging of results.
- Safety mechanisms to prevent overheating.

## Hardware Components
- **Device Under Test (DUT):** LM2596 DC-DC Converter
- **DAQ Module:** NI USB-6001
- **Load Resistors:** Four programmable resistors (3.3Ω, 4.7Ω, 6.8Ω, 10Ω)
- **Current Limiter:** LM317 regulator
- **LabVIEW Software:** For data acquisition and test automation

## Installation
1. Clone the repository:
2. Install LabVIEW and DAQmx drivers.
3. Connect the DUT and DAQ module as per the circuit diagram.
4. Run `validator_project.lvproj' dcdc_ in LabVIEW.
5. Run "interactive_tester.vi" for visualizing and Human-machine interface of Device Under Test. 

## Expected Results
| Load (Ω) | Input V (V) | Output V (V) | Efficiency (%) |
|----------|------------|------------|---------------|
| 10       | 7.53       | 3.00       | 73            |
| 4.7      | 7.52       | 3.00       | 71            |
| 1.3      | 7.6        | 3.00       | 68            |

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## GitHub Pages
For documentation, visit: https://nabeeljadoon.github.io/Hardware-in-the-Loop---LABVIEW/
