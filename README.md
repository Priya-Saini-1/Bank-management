This document provides an overview, installation steps, and instructions for using the program.

```markdown
# Bank Management System

## Overview
This **Bank Management System** is a simple console-based application written in C that allows users to:
- Create a new bank account.
- Deposit money into their account.
- Withdraw money from their account.
- Check their account balance.

The program stores account information in a file (`account.dat`) to maintain records across multiple executions.

## Features
- Stores account information securely in a binary file.
- Allows users to perform basic banking operations.
- Provides a menu-driven interface for ease of use.

## Requirements
To compile and run the program, ensure you have:
- A C compiler (GCC, Clang, or MSVC)
- A command-line interface (Terminal, Command Prompt, or an IDE with execution support)

## How to Compile and Run
Use the following steps to compile and execute the program:

### Compilation
```sh
gcc bank_management.c -o bank_management
```

### Execution
```sh
./bank_management
```

## Usage
Upon running the program, a menu will be displayed:

```
*** Bank Management System ***
1. Create Account
2. Deposit Money
3. Withdraw Money
4. Check Balance
5. Exit
Enter your choice: 
```

### Functionality
1. **Create Account** - Allows a user to register a new account with a unique account number.
2. **Deposit Money** - Enables the user to add funds to their account.
3. **Withdraw Money** - Deducts money from the account if sufficient balance is available.
4. **Check Balance** - Displays the current balance of the user's account.
5. **Exit** - Closes the application.

## File Handling
- The program uses `account.dat` to store account details in binary format.
- It reads and writes account information using file operations (`fopen`, `fread`, `fwrite`, `fseek`).

## Notes
- Ensure `account.dat` is in the same directory as the executable file.
- Account numbers must be unique to avoid duplication.

## Contributing
Feel free to enhance the program by adding features such as:
- Password authentication for accounts.
- Transaction history tracking.
- Interest calculation.

## License
This project is open-source and free to use for educational purposes.

## Developed by: Priya Saini 
## Date: May 2025
