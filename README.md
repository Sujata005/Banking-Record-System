# Banking Record System
A robust, console-based Banking Record System implemented in C++ that demonstrates core Object-Oriented Programming principles and persistent data storage using binary file handling.

## 🚀 Features
- **Persistent Storage**: Uses binary file handling (```.dat```) to ensure user data is saved even after the program terminates.

- **Account Management**: Create, Modify, and Delete accounts with 12-digit account number validation.

- **Transaction Processing**: Secure deposit and withdrawal functionalities with minimum balance checks for Savings and Current accounts.

- **Formatted Reporting**: Generates a clean, tabulated list of all registered account holders using ```iomanip```.

- **Input Validation**: Comprehensive checks for data types, account number length, and character inputs to prevent data corruption.

## 🛠️ Technical Stack
- **Language**: C++

- **Concepts**: Class & Objects, Encapsulation, File I/O (fstream), Exception Handling (Logic), Data Serialisation.

  ## 📂 Project Structure
  <img width="241" height="98" alt="image" src="https://github.com/user-attachments/assets/fc23ff47-6e98-4632-85a9-b8addd159d8c" />

## 🔧 How to Run
1. Clone the repository.

2. Compile using G++:
```g++ main.cpp -o BankingSystem```

3. Execute the program:
   ```./BankingSystem```
