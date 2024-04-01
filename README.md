# Storage Manager

This repository contains a C++ implementation of a Storage Manager. The Storage Manager is designed to efficiently allocate and deallocate memory from predefined memory pools. It includes functionality for both pool-based memory allocation and traditional heap-based allocation.

## Features

- **Pool-based Memory Allocation**: The Storage Manager allocates memory from predefined memory pools, improving efficiency and reducing fragmentation.
- **Dynamic Pool Creation**: New memory pools can be dynamically created as needed, allowing flexibility in managing memory.
- **Efficient Block Management**: The Storage Manager maintains information about free and used blocks within each pool for efficient allocation and deallocation.
- **Randomized Allocation and Deallocation**: The program demonstrates allocation and deallocation of memory with varying sizes and randomness, simulating real-world scenarios.
- **Performance Analysis**: The program measures the time taken for allocation and deallocation operations, providing insights into the efficiency of the Storage Manager compared to traditional heap allocation.

## Contents

- **sm.h**: Header file containing declarations of functions, structures, and macros used in the Storage Manager.
- **sm.cpp**: Source file containing the implementation of functions for initializing, allocating, deallocating, and destroying memory pools.
- **main.cpp**: Main program file demonstrating the usage of the Storage Manager for both pool-based and heap-based memory allocation.
- **README.md**: This file, providing an overview of the project, usage instructions, and other relevant information.

