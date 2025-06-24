C Graphical Calculator
This project implements a simple graphical calculator using C and the graphics.h library, typically found in environments like Turbo C++. It provides a user-friendly interface with a list of mathematical and trigonometric operations.

Features
Basic Arithmetic: Addition, Subtraction, Multiplication, Division, Remainder.

Powers & Roots: Square Root, Power (X 
Y
 ), Square (X 
2
 ), Cube (X 
3
 ).

Other Mathematical Functions: Reciprocal (1/X), Exponent, Factorial, Percentage, Logarithm.

Trigonometric Functions: Sine, Cosine, Tangent, Cosecant, Secant, Cotangent (all in degrees).

Graphical Interface: A menu of choices and an input/output display area are rendered using graphics.h.

How to Compile and Run (Turbo C++ Environment)
Save the Code: Save the provided C code as a .c file (e.g., calculator.c).

Ensure BGI Path: Make sure your TURBOC3 (or similar) directory contains the BGI folder, and the initgraph function call correctly points to it: "C:\\TURBOC3\\BGI".

Compile:

Open Turbo C++ IDE.

Load the calculator.c file.

Go to Compile -> Compile or press Alt + F9.

Link Graphics Library:

Go to Options -> Linker -> Libraries.

Ensure that Graphics Library is checked/selected.

Run:

Go to Run -> Run or press Ctrl + F9.

Usage
After running, a graphical window will appear showing a list of operations (1-20) on the left side.

In the text console (or within the graphics window if gotoxy is configured to print there), you will be prompted to "Choice".

Enter the number corresponding to the desired operation (e.g., 1 for Addition).

Follow the prompts to enter the required numerical inputs (X, Y).

The result will be displayed.

Press any key to exit the current operation and re-prompt for a new choice.

Limitations
This application is designed for legacy DOS-based C compilers like Turbo C++ and relies heavily on the conio.h and graphics.h libraries, which are not standard in modern C development environments.

The user interaction (input) still primarily happens in the console window, while the output graphics are displayed separately.

Error handling for invalid inputs (e.g., division by zero, non-numeric input) is minimal.
