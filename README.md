# Nand2Tetris — Part I: Hardware

Building a modern computer from first principles, starting with elementary logic gates and progressing toward a functional computer system. This project followed a course intended to teach computer hardware and software through creating a basic computer.

## Overview

This repository documents my implementation of the hardware projects from [Nand2Tetris Part I](https://www.nand2tetris.org/), based on *The Elements of Computing Systems* by Noam Nisan and Shimon Schocken.

Work was completed in the provided hardware simulator: [NAND2Tetris Hardware Simulator](https://nand2tetris.github.io/)

The course explores how computers work by constructing their hardware components layer by layer, using a simple Hardware Description Language (HDL).

**Primary objectives:**
- Understand how digital logic forms the foundation of computer hardware.
- Implement arithmetic and sequential logic circuits.
- Explore memory organization and processor architecture.
- Understand how machine-language instructions are executed by hardware.
- Develop a deeper understanding of the relationship between hardware components.

## Project Structure

| 01 | Boolean Logic | Logic gates, multiplexors, demultiplexors |

| 02 | Boolean Arithmetic | Adders, ALU, binary arithmetic |

| 03 | Sequential Logic | Flip-flops, registers, memory |

| 04 | Machine Language | Binary instructions, assembly, program execution |

| 05 | Computer Architecture | CPU, memory, instruction execution |

| 06 | Assembler | Translating assembly instructions into machine code |

## Technical Approach

The hardware components are implemented in simple HDL and tested using the same Nand2Tetris hardware simulation tools.

My approach was focused on understanding the logical thinking behind each chip. Through this project, I wanted to understand:
- How small components can combine into a larger function
- How binary logic can be used for more complex operations such as negative numbers and addition
- How computers sequentially track time
- How a computer works in basics

## Key Learnings

- **Digital logic:** How simple gates can lead to developing increasingly complex Boolean functions starting with the NAND gate.
- **Arithmetic hardware:** How binary arithmetic can be implemented using combinational circuits, including negative numbers through 2's complement.
- **Sequential logic:** How state and feedback allow circuits to store information across clock cycles.
- **Computer architecture:** How processing, memory, and control logic work together to execute instructions.

## Tools and Technologies

- **Hardware Description Language (HDL)** — describing digital circuits.
- **Nand2Tetris Hardware Simulator** — simulating and testing hardware implementations.
- **Git and GitHub** — version control and project documentation.

## Acknowledgments

This project follows the educational materials and assignments from [Nand2Tetris](https://www.nand2tetris.org/), created by Noam Nisan and Shimon Schocken, and the textbook *The Elements of Computing Systems*.
