# LED Blinking Example

This is a simple C code example for blinking an LED using a Microchip PIC microcontroller.

## Overview

The code demonstrates the basic functionality of turning an LED on and off in a continuous loop, creating a blinking effect. It uses the Microchip Code Configurator (MCC) generated files for system initialization.

## Table of Contents

- [Requirements](#requirements)
- [Setup](#setup)
- [Code Explanation](#code-explanation)
- [Usage](#usage)

## Requirements

- Microchip PIC microcontroller development environment
- MCC-generated files
- LED connected to pin RA4 on the microcontroller

## Setup

1. Clone this repository or download the provided code.
2. Set up your Microchip development environment.
3. Ensure the MCC-generated files and necessary header files are included in your project.
4. Connect an LED to pin RA4 on the microcontroller.

## Code Explanation

### Pin Definitions

The code defines macros for configuring the RA4 pin for controlling the LED.

### Delay Function

A simple delay function is implemented to create a 2-second delay using a loop based on the instruction cycle frequency.

### Main Function

The `main` function initializes the device and sets RA4 as an output. It enters an infinite loop, toggling the LED state every 2 seconds.

## Usage

1. Compile and program the code onto your Microchip PIC microcontroller.
2. Connect an LED to pin RA4 on the microcontroller.
3. Run the code, and the LED should blink on and off with a 2-second interval.


