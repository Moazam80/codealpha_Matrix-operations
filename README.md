# Matrix Operations in C

A clean, menu-driven C program that implements three fundamental
matrix operations: Addition, Multiplication, and Transpose.

## Features
- ✅ Matrix Addition (same-dimension matrices)
- ✅ Matrix Multiplication (with dimension validation)
- ✅ Matrix Transpose (rows ↔ columns)
- ✅ Interactive menu — run all operations in one session
- ✅ Supports matrices up to 10×10
- ✅ Modular code with separate functions for each operation

## How to Run

### Compile
gcc matrix_operations.c -o matrix_operations

### Execute
./matrix_operations

## Usage
Run the program and choose an option from the menu:
1 → Matrix Addition
2 → Matrix Multiplication
3 → Matrix Transpose
0 → Exit

Enter matrix dimensions and elements when prompted.
The result is displayed in a formatted grid.

## Concepts Covered
- 2D arrays in C
- Nested loops
- Functions with array parameters
- Memory initialization
- Modular programming

## Example (2×2 Addition)
Matrix A       Matrix B       Result
| 1  2 |   +  | 5  6 |   =  |  6   8 |
| 3  4 |      | 7  8 |      | 10  12 |

## Author
Made with  during my virtual C Language Internship at Code Alpha.
