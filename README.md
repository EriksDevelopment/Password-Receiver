# PasswordReceiver

A simple and interactive console application for generating strong and customizable passwords using C#.

## Features

- User-defined password length
- Options to include:
  - Letters (a-z, A-Z)
  - Numbers (0-9)
  - Symbols (!@#$%^&*, etc.)
- Ensures at least one character from each selected category is present
- Repeats password generation until the user chooses to quit
- Clear prompts and input validation

## How It Works

1. The program asks for the desired password length.
2. It prompts whether to include letters, numbers, and/or symbols.
3. It generates a random password based on your selections.
4. The password is displayed and you can choose to generate another or quit.

## Requirements

- .NET SDK (6.0 or later)
- C# compiler

## How to Run

Clone the repository and navigate to the project folder:

```bash
git clone https://github.com/yourusername/PasswordReceiver.git
cd PasswordReceiver
dotnet run
