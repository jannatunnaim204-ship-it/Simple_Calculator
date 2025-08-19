Simple Console-Based Calculator in C++
Description

This is a simple object-oriented calculator implemented in C++. It performs basic arithmetic operations: addition, subtraction, multiplication, and division. The program continues to perform calculations until the user inputs the = operator to display the final result.

The calculator uses a class temp to handle input, operations, and results.

Features

Perform continuous arithmetic operations while maintaining a running total.

Supports addition (+), subtraction (-), multiplication (*), and division (/).

Displays intermediate results after each operation.

Ends when the user enters the = operator, displaying the final result.

Requirements

C++ compiler (e.g., GCC, G++, or any IDE that supports C++)

Basic knowledge of C++ syntax

How to Use

Compile the program:

g++ calculator.cpp -o calculator


Run the executable:

./calculator


Enter the first value when prompted.

Enter an operator (+, -, *, /) followed by a second value.

The program will display the result and update the running total.

Repeat steps 4–5 for additional operations.

Enter = as the operator to display the final answer and exit.

Code Overview

Class temp: Handles the main calculator logic.

getValue1(): Input first value

getValue2(): Input second value

getOp(): Input operator

add(), sub(), mul(), divide(): Perform arithmetic operations

Main function: Runs the input loop until the operator is =.

Example
Enter the Value :: 10
Enter the Operator :: +
Enter the Value :: 5
10 + 5 :: 15
Enter the Operator :: *
Enter the Value :: 2
15 * 2 :: 30
Enter the Operator :: =
Final answer :: 30

Author

Jannatun Naim

License

This project is open-source and free to use for educational purposes.
