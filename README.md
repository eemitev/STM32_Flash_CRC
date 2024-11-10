# STM32 - Dynamic CRC Appender for Binary Files

## Overview

This project provides a solution for appending a Cyclic Redundancy Check (CRC) to the end of STM32 binary files. Unlike many examples found online where the CRC is stored at a fixed address, this implementation allows for a dynamic CRC location at the end of the image file.

## Features

- Dynamically calculates and appends CRC to STM32 binary files
- Supports variable-sized binary images
- Ensures data integrity for firmware images

## Why This Project?

While researching CRC implementations for STM32 projects, I noticed that most examples placed the CRC at a fixed address. If you want to program faster, and use a smaller file I developed this solution that appends the CRC at the end of the binary file, regardless of its size.

## Getting Started

### Prerequisites

- STM32CubeIDE (tested on Version: 1.12.1 Build: 16088_20230420_1057 MacOS)
- STM32 based board (tested on )
- Basic knowledge of STM32 programming and CRC concepts

### Installation

1. Clone this repository
2. Open the project in STM32CubeIDE
