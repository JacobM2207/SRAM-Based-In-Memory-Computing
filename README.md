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


![Sense_Amp_Schematic](https://github.com/JacobM2207/SRAM-Based-In-Memory-Computing/assets/122327307/9469eb75-ead2-48d3-9b2b-982dafdda1a7)

Image 3. Senses Amplifier Schematic


![amp_LAYOUT](https://github.com/JacobM2207/SRAM-Based-In-Memory-Computing/assets/122327307/41218771-c8f7-48f0-b8b4-46c9b48dfbb7)

Image 4. Sense Amplifier Layout

# Full Adder Module


![schematic](https://github.com/JacobM2207/SRAM-Based-In-Memory-Computing/assets/122327307/338c6d40-b0f2-4d9e-bc3d-7630d07f6c90)

Image 5. Full Adder Module Schematic


![layout](https://github.com/JacobM2207/SRAM-Based-In-Memory-Computing/assets/122327307/7d060018-62ca-46d5-9f7a-3be768804216)

Image 6. Full Adder Module Layout

# 64 x 64 SRAM Array Layout

![Full_Project](https://github.com/JacobM2207/SRAM-Based-In-Memory-Computing/assets/122327307/f57263dd-959f-44d9-b268-f4a1d9429ede)

Image 7. Full Layout
