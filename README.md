# Secure Password Generator

A Python-based password generator that creates strong and secure passwords using cryptographically secure randomness.  
The project allows users to customize password length and character composition while ensuring required security criteria are met.

## Features
- Cryptographically secure password generation using Python's `secrets` module
- Customizable password length
- Optional inclusion of numbers and special characters
- Guaranteed inclusion of required character types
- Password strength evaluation (Weak / Medium / Strong)
- Input validation for improved reliability
- Clean and modular code structure

## How It Works
1. User specifies the desired password length (minimum 8 characters).
2. User chooses whether to include numbers and special characters.
3. The program ensures required character types are included.
4. Remaining characters are generated securely and shuffled.
5. The final password and its strength are displayed.

## How It Works
https://github.com/himanihassija/Secure-Password-Generator/blob/main/Password%20Generator%20UI.jpeg

## Technologies Used
- Python
- secrets
- string

## Usage
Run the script and follow the on-screen prompts:

```bash
python password_generator.py

