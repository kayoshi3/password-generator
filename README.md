# Secure Password Generator

This project is a Python-based **secure password generator** designed to create customizable and random passwords for general-purpose use. It allows users to choose the desired password length (within security-safe limits) and whether to include **uppercase letters**, **numbers**, and **symbols**.

---

## Features

- Custom password length (8 to 32 characters)
- Optional inclusion of:
  - Uppercase letters
  - Numbers
  - Symbols
- Ensures at least one character from each selected category is included
- Randomized output with proper shuffling

---

## Sample Output

Sample output 1:
Welcome to the Password Generator!
Enter desired password length (8–32): 16
Include numbers? (y/n): y
Include symbols? (y/n): y
Include uppercase letters? (y/n): y

Generated Password: 9@qAjpvhK%tlr7de


Sample output 2:
Welcome to the Password Generator!
Enter desired password length (8–32): 15
Include numbers? (y/n): n
Include symbols? (y/n): y
Include uppercase letters? (y/n): y

Generated Password: v$}<:X,-mpx*(F?


> Output will vary every time due to randomness.

---

## How to Run

### Requirements:
- Python 3.6+

### Steps:
1. Clone the repository:

```bash
git clone https://github.com/eliven23/password-generator.git
cd password-generator

2. Run the script:
python password-generator.py


Planned Improvements / Learning Objectives
To enhance both functionality and maintainability of the project while deepening my understanding of secure coding practices, the following improvements are planned:

Switch to secrets module for cryptographically secure password generation

Add option to exclude ambiguous characters (e.g., l, 1, O, 0)

Refine symbol selection, limiting or customizing allowed special characters

Ensure minimum character type inclusion (at least one uppercase, one digit, etc.)

Improve input handling with thorough validation in the main() function

Provide password strength feedback based on length and character diversity

Enable generation of multiple passwords per request

Enhance user prompts and instructions for better usability

Separate UI from logic for modular, testable code

Add comprehensive docstrings and comments for clarity and documentation

