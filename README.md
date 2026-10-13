# Python Banking System

A command-line banking system built with Python as a learning project.

## Overview

The goal of this project is to practise Python fundamentals while building a simple banking simulation that runs entirely in the terminal. **No graphical user interface (GUI) is planned at this stage.**

> This is an educational project, not real banking software. Do not use real financial information or passwords.

## Planned Features

- Create and manage customer accounts
- Deposit and withdraw funds
- Check account balances
- View transaction history
- Account number and PIN-based login
- Transfer funds between accounts
- Save account data between runs using local storage
- Input validation and error handling

Features will be added incrementally as development progresses.

## Requirements

- Python 3.10 or newer
- No third-party packages are required for the initial version

## Getting Started

Clone the repository:

```bash
git clone https://github.com/shivamumrao2022-jpg/Banking-System.git
cd Banking-System
```

Run the application once the entry-point file has been added:

```bash
python main.py
```

On some systems, use `python3 main.py` instead.

## Project Structure

The planned structure is:

```text
Banking-System/
├── main.py          # Command-line menu and application entry point
├── account.py       # Account model and account operations
├── bank.py          # Banking logic
├── storage.py       # Data persistence
├── bank_data.json   # Local data file (created during development)
└── README.md
```

The structure may change as the project evolves. The application files are not all implemented yet.

## Development Roadmap

1. Build the main command-line menu.
2. Add account creation, deposits, withdrawals, and balance checks.
3. Add transaction history and validation.
4. Add persistent storage.
5. Add transfers and authentication.
6. Test edge cases and improve reliability.

## Learning Goals

- Python functions and modules
- Object-oriented programming
- File handling and JSON
- Input validation and exception handling
- Basic data modelling and testing

## Disclaimer

This project is for educational purposes only. It is not connected to a real bank and is not suitable for handling real money, payment credentials, or sensitive financial data.

## License

No license has been selected yet.
