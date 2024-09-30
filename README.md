# AckermannFunction

## Description
This Java project implements the Ackermann function, a classic example of a recursive function that grows extremely fast. The Ackermann function is defined recursively and demonstrates the concept of recursion in an impactful way. The program prints the result of several Ackermann function calls for different values of `m` and `n`.

## Author
Written by Mohammed Qutu.

## Requirements
- Java 21.0.2 or later

## Usage
To run the program, compile the `Ackermann.java` file and execute it. The program will compute and print the result of the Ackermann function for several pairs of `m` and `n` values.

### Example Output
1 2 3 4 5 7 29

### Key Features:
- **Recursive Function**: The Ackermann function is a well-known example of a highly recursive function that grows rapidly with increasing input values.
- **Recursive Method**: The `ackermann()` method demonstrates how to handle deep recursive calls in Java.

### Methods:
- `ackermann(int m, int n)`: Recursively computes the value of the Ackermann function based on the input values `m` and `n`.

### Example:
```java
System.out.println(ackermann(1, 2)); // Outputs: 4
System.out.println(ackermann(2, 2)); // Outputs: 7
System.out.println(ackermann(3, 2)); // Outputs: 29
