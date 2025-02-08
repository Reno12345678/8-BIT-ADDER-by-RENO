# 8-BIT-ADDER-by-RENO
Hello this is my 8-BIT ADDER project inspired by Hyperspace Pyrate
This project is a fully functional **8-bit adder** built using discrete components. It demonstrates the fundamental principles of binary addition using **2N3904 BJT transistors** as logic gates.

## Components Used

- **2N3904 BJT transistors**                                                                                                                                                         `152pcs`
- **220kΩ resistor for inputs**                                                                                                                                                      `184pcs`
- **47kΩ pull-up resistors**`50pcs`
- **LED**        `9pcs`                                                                                                                                              
- **PCB**          `8pcs`                  

## Overview

The adder is designed to take two 8-bit binary numbers as input and produce an 8-bit sum along with a carry-out bit. The circuit operates purely on discrete transistor logic without the use of integrated circuits.

## How It Works

Each bit of the adder is built using **transistor-based logic gates** that replicate standard digital addition circuits. The adder is composed of multiple **full-adders** connected in series to process each bit sequentially.

### Logic Implementation

- **Inputs**: A full-adder takes three inputs: two significant bits, `A` and `B`, and a carry-in bit`Cin`, from the previous stage.
- **Sum Calculation**: The sum output, `S`, is calculated using the formula: `S = A ⊕ B ⊕ Cin`, where `⊕` denotes the XOR (exclusive OR) operation.
- **Carry-Out Calculation**: The carry-out output, `Cout`, is determined using the formula: `Cout = (A AND B) OR (Cin AND (A ⊕ B))`.
- **Logic Gates**: The full-adder circuit consists of two XOR gates, two AND gates, and one OR gate to implement the sum and carry-out calculations.
- **Purpose**: Full-adders are used to add binary numbers and are the fundamental building blocks of arithmetic logic units (ALUs) in computers and other digital systems.
- **Outputs**: I used LEDs to represent the output bits.

## PCB

- **PCB is made in** [KiCAD](https://www.kicad.org/) **and produced in** [JLC PCB](https://jlcpcb.com/)
- [PCB GERBER](https://drive.google.com/file/d/1TC0HHmTJvVchm60jO_TXwn7dzBnb9_OO/view?usp=sharing) 

## Youtoube video

**-** just doing

## Other

This project is inspirated by [Hyperspace Pyrate](https://youtu.be/X31B1pVow1o?si=5MChZk4HNTxjwTem)
And if you want something you can type me on "reno888" discord
