# Stepper-motor-control-using-Nucleo
Stepper Motor Control using STM32 Nucleo F401RE and A4988 Driver:

This project provides a sample project for controlling a stepper motor using an STM32 Nucleo F401RE microcontroller board and an A4988 stepper motor driver. The project demonstrates how to configure the Nucleo board and driver, as well as how to generate step pulses and control the direction of the stepper motor.

## Hardware Requirements

- STM32 Nucleo F401RE development board
- A4988 stepper motor driver
- Stepper motor
- External power supply for the stepper motor (if required)
- Jumper wires

## Software Requirements

- STM32CubeIDE (Integrated Development Environment) or any other compatible IDE for STM32 microcontrollers

## Getting Started

1. Connect the STM32 Nucleo F401RE board to your computer using a USB cable.

2. Connect the A4988 stepper motor driver to the Nucleo board following the wiring instructions provided in the project code.

3. Install STM32CubeIDE on your computer if you haven't already.

4. Clone or download this repository to your local machine.

5. Open the project in STM32CubeIDE.

6. Build and flash the project to the STM32 Nucleo board.

7. Connect the stepper motor to the A4988 driver according to your motor's specifications.

8. Power up the setup and observe the stepper motor's movement based on the configured parameters in the code.

## Project Structure

Src: Contains the source code files.
Inc: Contains the header files.
main.c: Main program file containing the setup and control logic for the stepper motor.

## Configuration

- Adjust the GPIO pins used for controlling the DIR and STEP signals in the main.c file according to your hardware setup.
- Modify the code to set the desired speed, direction, and steps for the stepper motor as per your application requirements.
