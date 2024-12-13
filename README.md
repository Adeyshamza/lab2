README
# Basic Operations Program

This program is a simple C application that allows users to perform basic operations such as adding two integers, multiplying two floating-point numbers, reversing a string, and checking if two strings are similar. It also includes a debugging mode for additional output.

## Code Overview

### Files
- `main.c`: Contains the main logic and functions for the application.

### Functions

- `add()`: Prompts the user to enter two integers, computes their sum, and displays the result. If debugging is enabled, it provides additional debugging output.
- `multiply()`: Prompts the user to enter two floating-point numbers, computes their product, and displays the result. If debugging is enabled, it provides additional debugging output.
- `reverse()`: Prompts the user to enter a string (without whitespace), reverses the string, and displays the reversed string. If debugging is enabled, it provides additional debugging output.
- `similar()`: Prompts the user to enter two strings and checks if they are equal. If debugging is enabled, it provides additional debugging output.

### Debugging
- The program can be run in debug mode by passing the argument `debug` when running the executable. This will enable additional debugging output to help with troubleshooting.

### Usage

Compile the code with:

```sh
gcc -o operations_program main.c
