# Banking System

A simple **Banking System** implemented in C++ that allows users to create accounts, deposit and withdraw money, check balances, and manage account details.

## Features
- Create new bank accounts  
- Deposit money  
- Withdraw money  
- Check account balance  
- View account details  
- Store account data in files for persistence  

## Requirements
- C++ compiler (e.g., `g++`, `clang++`, or MSVC)  
- Standard C++ libraries (no external dependencies)  

## Build Instructions

### On Linux / macOS
```bash
g++ Banking\ System.cpp -o banking_system
./banking_system
```

### On Windows (MinGW)
```bash
g++ "Banking System.cpp" -o banking_system.exe
banking_system.exe
```

## Usage
- Run the compiled program.  
- Follow the on-screen menu to perform actions like creating accounts, depositing, or withdrawing funds.  
- Data is stored in a file, so accounts persist between runs.  

## File Structure
```
Banking System.cpp   # Main source code
```

## Future Improvements
- Add authentication (PIN or password per account)  
- Implement interest calculations  
- Add transaction history tracking  
- Provide a GUI frontend  
