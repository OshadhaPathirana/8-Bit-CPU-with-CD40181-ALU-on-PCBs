# 8-bit CPU Project

## Overview

Welcome to the 8-bit CPU project repository! This project was developed to gain a deeper understanding of CPU microarchitecture and the execution of instructions. The CPU is built using the CD40181 ALU, and all components are constructed on PCBs. The project was undertaken by Rusula Oshadha under the UpThrust Startup initiative.

## Features

- **8-bit Architecture**: The CPU operates on an 8-bit data width, allowing for simple yet educational instruction sets and operations.
- **CD40181 ALU**: The Arithmetic Logic Unit (ALU) at the heart of the CPU is based on the CD40181, a versatile and widely-used ALU chip.
- **PCB Construction**: All parts of the CPU are built on custom-designed PCBs, providing a solid and reliable hardware platform.
- **Educational Focus**: The primary goal of this project is to learn and demonstrate how CPU instructions are executed and how a CPU is architecturally structured.

## Project Goals

1. **Understand CPU Microarchitecture**: Gain a comprehensive understanding of the internal workings of a CPU, including control units, data paths, and instruction cycles.
2. **Learn Instruction Execution**: Explore how different instructions are fetched, decoded, and executed by the CPU.
3. **Hands-On Hardware Experience**: Build and test a functional CPU using discrete components and PCBs.

## Components

- **CD40181 ALU**: The core of the CPU, responsible for arithmetic and logical operations.
- **Control Unit**: Manages the fetching, decoding, and execution of instructions.
- **Registers**: Small, fast storage locations used to hold data and instructions temporarily.
- **Clock Generator**: Provides the timing signals necessary for synchronizing the operations of the CPU.
- **Memory**: Stores the program code and data for the CPU to process.
- **Bus System**: Facilitates data transfer between the CPU components.

## Repository Structure

```
8-bit-CPU-Project/
├── Schematics/             # Schematics 
├── PCB designs/            # PCB design files
├── images/                 # Photos and diagrams of the hardware
└── README.md               # Project overview and instructions
```

## Getting Started

### Prerequisites

- Basic understanding of digital electronics and microprocessors.
- Familiarity with PCB design and fabrication.
- Access to electronic components and tools for assembling the PCBs.

### Building the CPU

1. **Design the PCBs**: Use the schematic and PCB design files provided in the `hardware` directory to fabricate the PCBs.
2. **Assemble the Hardware**: Populate the PCBs with the required components, including the CD40181 ALU, registers, clock generator, and other necessary parts.
3. **Load the Program**: Use the sample programs in the `software` directory or write your own programs to test the CPU.
4. **Test and Debug**: Power up the CPU, run the programs, and use debugging tools to verify the correct operation of the CPU.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

## Acknowledgements

This project was made possible by the support and resources provided by UpThrust Startup. Special thanks to all who contributed to the development and testing of the CPU.

## Contact

For any questions or further information, please contact Rusula Oshadha at [].
