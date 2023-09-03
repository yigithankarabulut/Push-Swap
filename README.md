# Push Swap

## Overview

Push Swap is a sorting algorithm project developed using the QuickSort algorithm. The main objective of this project is to efficiently sort a stack of integers using a limited set of instructions. The goal is to find the shortest sequence of instructions to sort the stack with the smallest number at the top.

## Instructions

The project includes two programs:

- `push_swap`: This program takes an unsorted stack of integers as input and outputs a series of instructions to sort the stack efficiently. The instructions are separated by newline characters.

- `checker`: Checker is a program that takes a stack of integers and a series of instructions as input. It checks if the instructions correctly sort the stack. If the stack is sorted correctly, it outputs "OK"; otherwise, it outputs "KO."

## Usage

To compile the programs, use the provided Makefile:

- `make`: Compiles the `push_swap` program.

- `make bonus`: Compiles the `checker` program.

- `make all`: Compiles both `push_swap` and `checker`.

- `make fclean`: Removes all `.o` files and executable files.

- `make re`: Cleans the project by removing `.o` and executable files, and then recompiles both programs.

## Performance Metrics

- For sorting random 100 integers, the algorithm typically requires less than 700 moves.

- For sorting random 500 integers, the algorithm typically requires less than 5500 moves.

These metrics can be used as a reference for evaluating the efficiency of your sorting algorithm.

