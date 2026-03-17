# Simple Interest Calculator

A simple Python program to calculate simple interest based on user input for principal amount, rate of interest, and time period.

## Description

This program calculates simple interest using the formula:
```
Simple Interest = (Principal × Rate × Time) / 100
```

The program demonstrates basic type casting by converting user input strings to appropriate numeric types.

## Requirements

- Python 3.x
- No external dependencies required

## How to Run

### Method 1: Using Command Line

1. Open your terminal/command prompt
2. Navigate to the directory containing the file:
   ```bash
   cd "e:\Python\exp 1"
   ```
3. Run the script:
   ```bash
   python "simple intereset.py"
   ```
   
   Or using Python 3:
   ```bash
   python3 "simple intereset.py"
   ```

### Method 2: Using IDLE (Python's built-in IDE)

1. Open IDLE (Python IDE)
2. Go to `File` → `Open`
3. Navigate to and select `simple intereset.py`
4. Press `F5` or go to `Run` → `Run Module`

### Method 3: Using VS Code

1. Open VS Code
2. Open the folder `e:\Python\exp 1`
3. Right-click on `simple intereset.py`
4. Select "Run Python File in Terminal"

### Method 4: Double-click (Windows)

1. Ensure Python is installed and associated with `.py` files
2. Simply double-click on `simple intereset.py`
3. The program will run in a command window

## Usage

1. Run the program
2. Enter the principal amount when prompted
3. Enter the rate of interest when prompted  
4. Enter the time period when prompted
5. The program will display the calculated simple interest

### Example

```
Enter the principal amount: 10000
Enter the rate of interest: 5
Enter the time period: 3
The simple interest is: 1500.0
```

## Code Explanation

- `p = int(input("Enter the principal amount: "))` - Takes principal amount as integer
- `r = float(input("Enter the rate of interest: "))` - Takes rate as float (allows decimal values)
- `t = float(input("Enter the time period: "))` - Takes time period as float
- `si = (p * r * t) / 100` - Calculates simple interest using the standard formula
- `print("The simple interest is:", si)` - Displays the result

## Type Casting

The program demonstrates type casting by:
- Converting string input to integer for principal amount
- Converting string input to float for rate and time period

## File Structure

```
e:/Python/exp 1/
├── simple intereset.py    # Main Python script
└── README.md             # This documentation file
```

## Notes

- The program expects positive numeric values
- Invalid input will cause a ValueError
- The result is displayed as a floating-point number
