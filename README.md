# SRAM-Based-In-Memory-Computing
The goal of this project was to create a 64 x 64, 8T-SRAM with computing-in-memory (CiM) of addition of two 8-bit words. This will be implemented using Cadence Virtuoso for the schematic capture, Spectre for the circuit simulation, and Virtuoso Layout Suite for the layout.

# Introduction
The design principles of the von Neumann architecture have been prolific in the digital age. Still, its limitations have become apparent with the rise of AI and other computationally intense applications. An issue with this architecture is the bottleneck created when the CPU needs to interact with the memory constantly. Resulting in considerable energy and performance losses. A solution to this bottleneck is to implement Computing-in-Memory(CiM). Instead of having separate compartments for processing and memory, some of the computation is done in the memory itself. Having localized logical computational circuitry will increase performance and decrease the need for the CPU to interact with remote memory units.

# 8T SRAM Design
![8TSRAM_DARK](https://github.com/JacobM2207/SRAM-Based-In-Memory-Computing/assets/122327307/3e388c3d-413e-4d8e-a3a5-de5d00254bd7)
Image 1. 8T-SRAM Schematic


![8TSRAMV4Layout_DARK](https://github.com/JacobM2207/SRAM-Based-In-Memory-Computing/assets/122327307/0e675d09-d600-4c67-a899-ed0985904eba)
Image 2. 8T-SRAM Layout

# Sense Amplifier

