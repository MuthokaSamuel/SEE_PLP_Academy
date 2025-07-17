Simple Calculator
A minimal Python script that performs basic arithmetic operations (addition, subtraction, multiplication, and division) on two numbers entered by the user.

Features
Prompts the user to input two numbers.

Calculates:

Addition

Subtraction

Multiplication

Division (handles division by zero gracefully)

Displays the result of each operation.

How to Use
Make sure you have Python installed (version 3.x recommended).

Download or copy the script to your machine (calculator.py, for example).

Run the script from the command line:

bash
python calculator.py
Follow the prompts to enter two numbers. The script will display the results of each arithmetic operation.

Example Usage
text
Enter first number: 10
Enter second number: 5
Addition: 10.0 + 5.0 = 15.0
Subtraction: 10.0 - 5.0 = 5.0
Multiplication: 10.0 * 5.0 = 50.0
Division: 10.0 / 5.0 = 2.0
If you try to divide by zero:

text
Enter first number: 7
Enter second number: 0
Addition: 7.0 + 0.0 = 7.0
Subtraction: 7.0 - 0.0 = 7.0
Multiplication: 7.0 * 0.0 = 0.0
Division: 7.0 / 0.0 = Undefined (cannot divide by zero)
Notes
All operations are performed on floating-point input for maximum flexibility.

Division by zero is safely handled with an informative message.
