# ISAT Subtask 2 – Number Conversion Program

## Project Overview

This project is part of the **Integrated Summative Assessment (ISA) – Subtask 2** for **NC(V) Introduction to Technical Programming Level 3**.

The project extends an existing decimal-to-binary and binary-to-decimal converter program by adding additional conversion functions and a user-friendly menu-driven command-line interface.

The program can convert between **decimal, binary, and hexadecimal** number systems.

## Features

The program includes four conversion functions:

1. **Decimal to Binary**
2. **Binary to Decimal**
3. **Decimal to Hexadecimal**
4. **Hexadecimal to Decimal**

It also includes:

* A menu-driven interface
* A Demo option
* Random number generation
* Input validation
* An Exit option

## Menu Options

When the program starts, the following menu is displayed:

```text
======================================
       NUMBER CONVERSION PROGRAM
======================================
1. Convert Decimal to Binary
2. Convert Binary to Decimal
3. Convert Decimal to Hexadecimal
4. Convert Hexadecimal to Decimal
5. Demo
6. Exit
======================================
```

## Conversion Functions

### Decimal to Binary

The `decimalToBinary()` function receives an integer and returns its binary equivalent as a string.

Example:

```text
10 Decimal = 1010 Binary
```

### Binary to Decimal

The `binaryToDecimal()` function receives a string containing binary digits and returns the decimal equivalent.

Example:

```text
1010 Binary = 10 Decimal
```

### Decimal to Hexadecimal

The `decimalToHexadecimal()` function receives an integer and returns its hexadecimal equivalent as a string.

Example:

```text
255 Decimal = FF Hexadecimal
```

### Hexadecimal to Decimal

The `hexadecimalToDecimal()` function receives a hexadecimal string and returns its decimal equivalent.

Example:

```text
FF Hexadecimal = 255 Decimal
```

## Demo

The Demo option generates a random number between **0 and 99**.

The generated number is then converted to binary and displayed.

Example:

```text
========== DEMO ==========
Random number generated: 73
Binary equivalent: 1001001
==========================
```

The random number will be different each time the Demo option is selected.

## Input Validation

The program checks user input to help prevent invalid conversions.

For binary numbers, only:

```text
0 and 1
```

are accepted.

For hexadecimal numbers, the valid characters are:

```text
0-9 and A-F
```

Both uppercase and lowercase hexadecimal letters are supported.

## Technologies Used

* **Programming Language:** C++
* **Version Control:** Git
* **Repository:** GitHub
* **Interface:** Command-line interface (CLI)

## How to Run the Program

1. Clone or download the repository.
2. Open the project in a C++ IDE such as Visual Studio, Code::Blocks, Dev-C++, or another C++ development environment.
3. Compile the program.
4. Run the program.
5. Select an option from the menu.
6. Enter the required number.
7. View the conversion result.

## GitHub Version Control

GitHub was used to track the development of the project.

The project was developed through multiple commits, including:

* Initial converter program
* Decimal to binary conversion function
* Binary to decimal conversion function
* Decimal to hexadecimal conversion function
* Hexadecimal to decimal conversion function
* Menu and Demo options
* Final testing and improvements

## Testing

The program was tested using different decimal, binary, and hexadecimal values.

Examples:

| Conversion            | Input | Expected Output |
| --------------------- | ----: | --------------: |
| Decimal → Binary      |    10 |            1010 |
| Decimal → Binary      |    25 |           11001 |
| Binary → Decimal      |  1010 |              10 |
| Binary → Decimal      | 11001 |              25 |
| Decimal → Hexadecimal |   255 |              FF |
| Decimal → Hexadecimal |   100 |              64 |
| Hexadecimal → Decimal |    FF |             255 |
| Hexadecimal → Decimal |    64 |             100 |

## Conclusion

This project demonstrates the use of C++ functions, loops, selection statements, strings, random number generation, input validation, and a menu-driven interface.

GitHub is used to manage the project and track changes through commits. The project demonstrates how an existing program can be extended with new functionality while using version control during the development process.
