MINI CALCULATOR 
A lightweight, terminal-based calculator built with Python. This project demonstrates basic arithmetic operations and error handling for user inputs.
🚀 Features:-
★Arithmetic Operations: Supports addition (+), subtraction (-), multiplication (*), and division (/).
★Division Guard: Includes logic to prevent "Division by Zero" errors.
★Input Validation: Alerts the user if an unsupported operator is entered.
★Float Support: Handles both integers and decimal numbers

Prerequisites: 
1.Ensure you have Python installed on your system.
2.Run the script: Navigate to the directory containing the file and run:
python "Python project"

3.Calculate:
Enter your first number.
Enter an operator (+, -, *, /).
Enter your second number.
View the result instantly in the terminal.

📂 Code Snippet
The logic uses a simple if-elif-else structure to process the math:
if operator == "+":
    print("Result:", num1 + num2)
elif operator == "/":
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Error: Cannot divide by zero")
        
📜 License
This project is open-source and available for educational purposes.
