# PWguard_cli

`pwguard_cli` is a simple **Command Line Interface (CLI)** tool written in Python that allows users to:
- Check password strength
- Generate secure random passwords
- Display the SHA-256 hash of a password

This project is designed for learning basic password security concepts and local password management without relying on cloud services.

---

## Features

- Evaluate password strength based on:
  - Length
  - Uppercase and lowercase letters
  - Digits
  - Symbols
- Generate random, human-readable passwords (avoids confusing characters like `0`, `O`, `1`, `l`)
- Display SHA-256 hash of any password
- Interactive CLI menu for ease of use

---

## Installation

Make sure you have **Python 3.7+** installed.

```bash
# Clone this repository
git clone https://github.com/RadEner/PWguard_cli.git

# Navigate to the project directory
cd PWguard.cli

# Run the program
python3 PWguard_cli.py
