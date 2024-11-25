# calculator
This Python program creates a graphical user interface (GUI) for a simple calculator using the tkinter library. The calculator allows users to perform basic arithmetic operations, including addition, subtraction, multiplication, and division, along with support for parentheses. 
Key Components:
Calculation Logic:
The calculator keeps track of the ongoing calculation using a global variable calculation.
The eval() function is used to evaluate the mathematical expression in calculation.

Functions:
add_to_cal(symbol): Adds the selected digit or operator to the current calculation and updates the display.
evaluate_calculation(): Evaluates the entered mathematical expression and displays the result or an error message.
clear_field(): Resets the calculation and clears the display.

UI Design:
Buttons: Each button corresponds to a digit, operator, or special character and is placed in an intuitive layout using the grid() method.
Display: A text field at the top shows the current calculation or result.
Font: Arial font is used for both the display and buttons, ensuring readability.

Grid Layout:
Buttons are arranged logically in rows and columns:
Rows 2–5: Number buttons (1-9), 0, and parentheses.
Column 4: Operator buttons (+, -, *, /).
Row 6: Equal (=) and Clear (C) buttons.
