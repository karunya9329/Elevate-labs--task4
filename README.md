# Elevate-labs--task4
Overview

This project is a simple Java calculator application designed to demonstrate core Java programming concepts such as methods, method overloading, exception handling, pass-by-value behavior, and clean code structure.
Each arithmetic operation is implemented as a separate method, and the program is structured to be easy to understand, reusable, and testable.

Objectives

The application demonstrates:
Creating a calculator with separate methods for each operation
Method overloading using different parameter types
Reusable utility methods
Effective use of return values
Java pass-by-value behavior
Exception handling for divide-by-zero
Code structure that reduces redundancy
Independent testing of each method

Technologies Used
Language: Java
JDK Version: Java 8 or higher
IDE (Optional): IntelliJ IDEA / Eclipse / VS Code

Project Structure
CalculatorApp.java
README.md
All logic is contained in a single file for simplicity.

Supported Operations

Addition (int and double)
Subtraction
Multiplication
Division (with exception handling)
Key Concepts Demonstrated

Method Overloading
add(int a, int b)
add(double a, double b)
Same method name with different parameter types.

Reusable Utility Method
checkDivideByZero(int divisor)
Used to avoid redundant divide-by-zero checks.

Exception Handling
Division by zero is handled using try-catch and ArithmeticException.

Pass-by-Value in Java

Java passes copies of variables, not the actual variables.
Changes made inside a method do not affect the original value.
 Independent Method Testing
Each method is tested separately inside the main() method.

 How to Run the Program

Save the file as:
CalculatorApp.java
Compile the program:
javac CalculatorApp.java
Sample Output
Addition (int): 15
Addition (double): 15.7
Subtraction: 12
Multiplication: 24
Division: 5.0
Error: Division by zero is not allowed.
Original number after method call: 100

 Future Enhancements

Menu-driven calculator
Object-oriented design using multiple classes
JUnit test cases
GUI-based calculator (Swing / JavaFX)

 Author
 Karunya 
