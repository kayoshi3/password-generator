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


