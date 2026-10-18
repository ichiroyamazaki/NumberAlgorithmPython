# NumberAlgorithmPython

NumberAlgorithmPython is a simple Python program that compares two integers and determines whether the first number is less than, greater than, or equal to the second number.

## Overview

This project demonstrates basic Python programming concepts, including user input, integer conversion, conditional statements, and comparison operators.

The program asks the user to enter two numbers, compares their values, and displays the appropriate result.

## Features

- **User Input:** Accepts two numbers from the user.
- **Integer Conversion:** Converts the entered values into integers.
- **Number Comparison:** Determines whether the first number is less than, greater than, or equal to the second number.
- **Conditional Statements:** Uses `if`, `elif`, and `else` to evaluate the comparison.
- **Console Output:** Displays the comparison result in the terminal.

## Requirements

- Python 3
- A Python-compatible IDE or code editor, such as Visual Studio Code, IDLE, or PyCharm

## Installation

1. Install Python from the official website: https://www.python.org/downloads/
2. Clone or download this repository:

   ```bash
   git clone https://github.com/ichiroyamazaki/NumberAlgorithmPython.git
   ```

3. Open the project folder in your preferred Python IDE.
4. Locate `NumberAlgorithm.py`.

## How to Run

Run the following command in your terminal from the project directory:

```bash
python NumberAlgorithm.py
```

If your system uses `python3`, run:

```bash
python3 NumberAlgorithm.py
```

## Example

```text
Enter the first number: 10
Enter the second number: 20
The first number is less than the second number.
```

Another example:

```text
Enter the first number: 30
Enter the second number: 15
The first number is greater than the second number.
```

If both numbers are equal, the program displays:

```text
Enter the first number: 5
Enter the second number: 5
The first number is equal to the second number.
```

## How It Works

1. The program requests the first number.
2. It requests the second number.
3. Both inputs are converted into integers.
4. The program compares the two values using conditional statements.
5. It prints the appropriate comparison result.

## Project Structure

```text
NumberAlgorithmPython/
├── NumberAlgorithm.py
└── README.md
```

## Project Information

- **Project Name:** NumberAlgorithmPython
- **Language:** Python
- **Application Type:** Console-based program
- **Main File:** `NumberAlgorithm.py`
- **Developer:** Ichiro Yamazaki

## Limitations

- Accepts integer values only.
- Non-numeric input causes a conversion error.
- Does not include a graphical user interface.
- Compares only two numbers per execution.

## Future Improvements

- Add validation for invalid input.
- Support decimal numbers.
- Allow repeated comparisons without restarting the program.
- Display more detailed comparison results.

## License

No license has been specified in the repository. All rights remain with the author unless otherwise stated.
