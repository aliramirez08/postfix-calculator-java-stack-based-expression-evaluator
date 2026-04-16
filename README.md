# Java Postfix Calculator

This project implements an interactive Postfix (Reverse Polish Notation) Calculator in Java using a stack-based algorithm. It evaluates postfix expressions by pushing operands onto a stack and applying operators in sequence. The program supports both integer and floating-point numbers, allowing users to input expressions and receive immediate results.

## Features

- Evaluates postfix expressions
- Supports floating-point arithmetic
- Handles operators: +, -, *, /, %
- Detects invalid input and errors
- Continuous user input until exit

## Concepts Demonstrated
- Stacks (data structures)
- Expression evaluation
- Algorithm design
- Error handling and validation

## Technologies Used
- Java
- JDK 11+

## Project Structure
- `PostfixCalculator.java` – Main program with stack logic

## How to Run

### Prerequisites
- Java Development Kit (JDK 11+)

## How to Run

### Prerequisites
- Java Development Kit (JDK 11+)

### Steps
```bash
javac PostfixCalculator.java
java PostfixCalculator
```

## Example Output
```text
Expression: 3.5 1.5 +
Result: 5.0000

Expression: 10 2 /
Result: 5.0000
```

## What I Learned
This project helped me understand how stacks are used to evaluate expressions and how operators are applied in postfix notation. It also improved my ability to handle edge cases and user input errors.

## Future Improvements
- Add GUI interface
- Support more operations
- Improve error messaging

## Screenshots

### Calculator Interface
![Postfix Calculator](Screenshots/PostfixCalculator.png)

### Additional Example
![Postfix Calculator Example](Screenshots/PostfixCalculator2.png)

### Output Result
![Program Output](Screenshots/output.png)
