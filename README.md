# Coin Change Calculator
 
This simple C program calculates the minimum number of coins to be given as change for a specified amount in cents. The program prompts the user to input the number of cents they are owed and then calculates the optimal distribution of quarters, dimes, nickels, and pennies.

### Usage
To use the program, compile the source code using a C compiler and run the executable. Follow the on-screen prompts to input the number of cents. The program will then output the total number of coins needed to make up that amount.

### Code Structure
The code consists of several functions:

-get_cents: Prompts the user for the number of cents, ensuring a non-negative input.

-calculate_quarters, calculate_dimes, calculate_nickels, calculate_pennies:
These functions calculate the number of quarters, dimes, nickels, and pennies needed, respectively.

-The main function orchestrates the execution of the program by calling these functions and displaying the final result.

### How to Compile and Run
1-Ensure you have a C compiler installed on your system.
2-Open a terminal and navigate to the directory containing the source code.
3-Compile the code using the following command:


gcc change_calculator.c -o change_calculator -lcs50

4-Run the executable:

./change_calculator

### Example

Please enter the number of cents:
87
4

In this example, the user is owed 87 cents, and the program calculates that the minimum number of coins required is 4 (3 quarters and 1 dime).

### Contributions
Feel free to contribute to the project by forking the repository, making improvements, and submitting pull requests.

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.






