# Password_strength_checker
## Introduction

Password Strength Checker is a Python script that evaluates the strength of a password you provide. It analyzes factors like lowercase letters, uppercase letters, digits, special characters, and whitespace, and gives you a password strength score along with remarks on the password's security level.

## Usage

1. Clone the repository or download the script file.
2. Run the script using a Python interpreter.
3. Follow the prompts to enter the password you want to evaluate.

## Functionality

The script performs the following functions:
- Collects a password from the user securely (without displaying it on the screen).
- Analyzes the password's composition based on lowercase letters, uppercase letters, digits, special characters, and whitespace.
- Calculates a password strength score from 0 to 1 (with 1 being the strongest).
- Provides remarks on the password's security level.

## How It Works

The script uses the `getpass` module to securely collect the password without displaying it on the screen. It then counts the occurrences of lowercase letters, uppercase letters, digits, special characters, and whitespace. Based on these counts, a strength score is calculated, and corresponding remarks are provided.

## Requirements

- Python 3.x
