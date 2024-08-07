# Documentation added by me 
# Basic Calculator Project Documentation

## Overview
This document provides an analysis of the code structure and functionality of a basic calculator project implemented in C++.

## Class: BasicMath
The `BasicMath` class provides basic arithmetic operations including addition, subtraction, multiplication, division, and modulus.

### int addnum(int x, int y)
Adds two integers and returns the result.
- **Parameters**:
  - `int x`: First integer
  - `int y`: Second integer
- **Return Value**: The sum of `x` and `y`

### int subnum(int x, int y)
Subtracts the second integer from the first and returns the result.
- **Parameters**:
  - `int x`: First integer
  - `int y`: Second integer
- **Return Value**: The difference between `x` and `y`

### int multnum(int x, int y)
Multiplies two integers and returns the result.
- **Parameters**:
  - `int x`: First integer
  - `int y`: Second integer
- **Return Value**: The product of `x` and `y`

### int divnum(int x, int y)
Divides the first integer by the second and returns the result.
- **Parameters**:
  - `int x`: Numerator
  - `int y`: Denominator
- **Return Value**: The quotient of `x` and `y`
- **Note**: The function does not handle division by zero explicitly.

### int modnum(int x, int y)
Computes the remainder of the division of the first integer by the second and returns the result.
- **Parameters**:
  - `int x`: Numerator
  - `int y`: Denominator
- **Return Value**: The remainder of the division of `x` by `y`

## Main Function
The `main` function handles user input and calls the appropriate functions based on the user's choice.

### Workflow
1. Prompts the user to enter two integers (`x` and `y`).
2. Asks the user to select a mathematical operation from the following options:
   - Add Numbers (`A`)
   - Subtract Numbers (`S`)
   - Multiply Numbers (`M`)
   - Divide Numbers (`D`)
   - Get the remainder of Numbers (`G`)
3. Based on the user's choice, calls the corresponding function from the `BasicMath` class and displays the result.

### Input and Output
- **Input**:
  - Two integers from the user.
  - A character representing the chosen mathematical operation.
- **Output**:
  - The result of the chosen operation applied to the input integers.
  - An error message if the user inputs an invalid choice or attempts an invalid operation (e.g., division by a non-positive number).
