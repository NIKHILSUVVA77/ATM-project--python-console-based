# ATM-project--python-console-based
# Banking System

This is a simple banking system implemented in Python. It allows users to perform basic banking operations such as withdrawing money, depositing money, generating a PIN, and viewing a mini statement.

## Features

- Withdraw money
- Deposit money
- PIN generation
- Mini statement

## How to Run

1. Ensure you have Python installed on your system.
2. Copy the code into a Python file, e.g., `banking_system.py`.
3. Open a terminal or command prompt.
4. Navigate to the directory containing the Python file.
5. Run the program using the command:

## Code Explanation

The code defines a dictionary called `accounts`, which stores account information in the following format:

The program enters an infinite loop and presents a menu with the following options:
1. Withdraw
2. Deposit
3. Pin Generation
4. Mini Statement
5. Exit

### Withdraw
- Prompts the user to enter their account number.
- Checks if the account number is valid.
- Checks if a PIN has been generated for the account.
- Prompts the user to enter their PIN.
- Checks if the PIN is valid.
- Prompts the user to enter the amount to withdraw.
- Checks if the account has sufficient balance.
- Deducts the amount from the balance if sufficient funds are available.

### Deposit
- Prompts the user to enter their account number.
- Checks if the account number is valid.
- Prompts the user to enter the amount to deposit.
- Adds the amount to the account balance.

### Pin Generation
- Prompts the user to enter their account number.
- Checks if the account number is valid.
- Checks if a PIN has already been generated for the account.
- Prompts the user to enter a new PIN.
- Updates the account with the new PIN.

### Mini Statement
- Prompts the user to enter their account number.
- Checks if the account number is valid.
- Prompts the user to enter their PIN.
- Checks if the PIN is valid.
- Displays the account holder's name, email, and balance.

### Exit
- Exits the program.
