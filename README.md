# C++ Input and Output: Hello World and Calculator Program

## Aim
To study the basics of input and output operations in C++ and implement simple programs including a "Hello World" program and a basic calculator.

---

## Software Required
Visual Studio

---

## Theory
In C++, input and output operations are handled using *streams*, which represent a flow of data in the form of bytes.  

- **Input Stream**: When the flow of data goes from an input device (e.g., keyboard) to the main memory, it is called input.  
- **Output Stream**: When the flow of data goes from the main memory to an output device (e.g., display screen), it is called output.  

All standard streams are defined in the `<iostream>` header file, which provides tools for basic input and output in C++. The most commonly used objects are:  

1. **`cout` (Standard Output Stream)**  
   - Belongs to the `iostream` class.  
   - Used to display output on the screen.  
   - Works with the *insertion operator* `<<` to send data to the output stream.  
   - Example:  
     ```cpp
     cout << "Hello World";
     ```

2. **`cin` (Standard Input Stream)**  
   - Belongs to the `istream` class.  
   - Used to read input from the keyboard.  
   - Works with the *extraction operator* `>>` to take data from the user and store it in a variable.  
   - Example:  
     ```cpp
     int x;
     cin >> x;
     ```

---

## Implementation
In this practical, two basic programs were created to demonstrate input and output handling in C++:  

1. **Hello World Program**  
   - Prints a simple message "Hello World" to the screen using `cout`.  
   - Demonstrates the standard output mechanism in C++.  

2. **Simple Calculator**  
   - Takes two numbers as input using `cin`.  
   - Performs basic arithmetic operations such as addition, subtraction, multiplication, and division using arithmetic operators (`+`, `-`, `*`, `/`).  
   - Displays the results using `cout`.  

These programs introduce the fundamentals of input/output operations and set the foundation for further programming in C++.  

---

## Conclusion
Through this practical, I learned about the use of `cin` and `cout` for handling input and output in C++. I also implemented two programs: a "Hello World" example to demonstrate output, and a basic calculator to combine both input and arithmetic operations.
