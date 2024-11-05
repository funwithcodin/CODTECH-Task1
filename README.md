Name: MAYUKH BANERJEE
Company: CODTECH IT SOLUTIONS
ID: CT3MTDS68
Domain: Java Programming
Duration: August 5th to November 5th, 2024
Mentor: MUZAMMIL AHMED

Overview of the Basic Calculator Project:
The Basic Calculator project is a console-based Java application designed to perform simple arithmetic operations. This program enables users to input two numbers and choose an operation from addition, subtraction, multiplication, and division. It then computes and displays the result, providing an interactive experience through the command line.

Objectives:
1. User Interaction: To prompt users for input, including two numbers and their desired arithmetic operation.
2. Arithmetic Operations: To perform basic arithmetic calculations (addition, subtraction, multiplication, and division) based on user input.
3. Error Handling: To implement basic error handling, particularly for division by zero.
4. Continuous Operation: To allow users to perform multiple calculations without restarting the application.
5. User-Friendly Interface: To provide clear instructions and feedback to the user throughout the operation.

Key Activities:
1. Input Handling:
Use Scanner to read user input from the console.
Prompt the user to enter two numbers.
2. Operation Selection:
Display a menu of arithmetic operations for the user to choose from.
Capture the user’s choice and validate the input.
3. Calculation Logic:
Use a switch statement to perform the selected operation.
Handle division with a special case to prevent division by zero.
4. Output Display:
Display the results of the calculations clearly to the user.
Provide feedback for invalid operations or input.
5. Looping for Continuity:
Implement a loop to allow users to perform multiple calculations.
Ask if the user wants to continue or change the numbers for the next operation.
6. Resource Management:
Properly close the Scanner object at the end of the program to prevent resource leaks.

Technology Used:
Programming Language: Java
Utilized for its strong support for console applications and object-oriented programming principles.
Development Environment:
Any standard Java IDE (such as IntelliJ IDEA, Eclipse, or NetBeans) can be used to develop and run the application.
Java Standard Library:
java.util.Scanner: Used for reading user input from the console.

Code Explanation:

Input Initialization: The program initializes a Scanner object to read user input, prompting for two integers.
Loop for Operations: A while loop allows the user to perform calculations repeatedly until they choose to exit.
Operation Selection: A switch statement processes the user's choice of arithmetic operations:
Addition: Computes the sum of the two numbers.
Subtraction: Computes the difference between the two numbers.
Multiplication: Computes the product of the two numbers.
Division: Computes the quotient, with a check to avoid division by zero.
User Feedback: The program outputs results and prompts the user to decide whether to perform more calculations or change the input numbers.
Termination: The loop can terminate based on user input, and resources are freed with scanner.close().

Conclusion:
The Basic Calculator project serves as an excellent introductory exercise for understanding user input handling, control flow, and basic arithmetic operations in Java. It provides a solid foundation for further enhancements, such as supporting more advanced operations or developing a graphical user interface (GUI) in future iterations.
![Command Prompt 05-11-2024 23_02_59](https://github.com/user-attachments/assets/35e6ca62-ebdc-40e6-a5fe-0b45583f2d50)
