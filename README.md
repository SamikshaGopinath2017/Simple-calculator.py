# Simple Calculator

A basic command-line calculator written in Python that performs fundamental arithmetic operations.

## Features

- Addition
- Subtraction
- Multiplication
- Division (with zero-division protection)
- Interactive menu-driven interface
- Input validation

## How to Use

1. Run the program:
   ```bash
   python calculator.py
   ```

2. Choose an operation from the menu:
   - Enter `1` for Addition
   - Enter `2` for Subtraction
   - Enter `3` for Multiplication
   - Enter `4` for Division
   - Enter `5` to Exit

3. Enter two numbers when prompted

4. View the result and choose another operation or exit

## Example

```
Simple Calculator
1. Add
2. Subtract
3. Multiply
4. Divide
5. Exit
Choose operation (1/2/3/4/5): 1
First number: 10
Second number: 5
10.0 + 5.0 = 15.0
```

## Requirements

- Python 3.x

## Error Handling

- Prevents division by zero
- Validates menu choices
- Handles invalid number inputs gracefully
