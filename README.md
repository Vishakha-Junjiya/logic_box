# ⭐ Pattern Generator and Number Analyzer

## 📌 Project Overview

The Pattern Generator and Number Analyzer is a beginner-friendly Python project that generates a star pattern and analyzes a range of numbers.

This project combines two different programming tasks into one menu-driven program. It helps demonstrate the practical use of Python fundamentals, including loops, conditional statements, user input, range function, and arithmetic operations.

## ✨ Features

* ⭐ Generate a star pattern based on the number of rows.
* 🔢 Check whether numbers are Even or Odd.
* ➕ Calculate the sum of numbers in a given range.
* ⌨️ Take user input through the terminal.
* 🔄 Use a menu-driven program with an exit option.
* ⚠️ Handle invalid input such as an incorrect range or non-positive number of rows.

## 🐍 Python Concepts Used

### 1. 🔁 While Loop

A `while` loop is used to repeatedly execute a block of code as long as a condition is true.

In this project, the while loop keeps displaying the menu until the user chooses the exit option.

```python
while True:
    print("1. Generate a Pattern")
    print("2. Analyze a Range of Numbers")
    print("3. Exit")
```

### 2. 🔄 For Loop

A `for` loop is used to iterate over a sequence or range of values.

In this project, it is used to generate the star pattern and analyze each number in a given range.

```python
for i in range(1, rows + 1):
    print("*" * i)
```

### 3. 🔀 If-Else Statements

If-else statements are used to make decisions based on conditions.

This project uses conditional statements to check whether a number is even or odd and to validate user input.

```python
if no % 2 == 0:
    print("Even")
else:
    print("Odd")
```

### 4. 🔢 Range Function

The `range()` function generates a sequence of numbers. It is commonly used with for loops.

In this project, range is used to generate rows of stars and iterate through a range of numbers.

```python
range(1, 5)
```

Output sequence:

```text
1, 2, 3, 4
```

### 5. ⌨️ User Input

The `input()` function is used to take data from the user.

This project takes the number of rows, starting number, and ending number as input.

```python
rows = int(input("Enter number of rows: "))
```

### 6. ➕ Arithmetic Operators

Arithmetic operators are used to perform mathematical calculations.

The modulo operator `%` is used to check whether a number is even or odd, and the addition operator `+` is used to calculate the sum.

```python
if no % 2 == 0:
    print("Even")

sum = sum + no
```

### 7. 🧮 Variables

Variables are used to store values during program execution.

This project uses variables such as `rows`, `start`, `end`, `no`, and `sum` to store input and calculation results.

### 8. 🛡️ Input Validation

Input validation means checking whether the user has entered valid data.

In this project, the program checks that the number of rows is positive and that the ending number is not smaller than the starting number.

## 🔄 Program Workflow

1. 👋 Display the welcome message.
2. 📋 Display the menu with three options.
3. ⭐ Generate a Pattern – Ask for the number of rows and print a star pattern.
4. 🔢 Analyze a Range of Numbers – Ask for the starting and ending numbers.
5. 🔍 Check each number as Even or Odd.
6. ➕ Calculate and display the sum of the numbers.
7. 🚪 Exit the program when the user selects option 3.

## ⭐ Pattern Generation

The pattern generator prints stars in increasing rows.

For example, if the user enters 5 rows, the output will be:

```text
*
**
***
****
*****
```

The program uses a for loop to print the required number of stars in each row.

## 🔢 Number Analysis

The number analyzer checks each number in the selected range.

For example, if the user enters 1 to 5:

```text
1 - Odd
2 - Even
3 - Odd
4 - Even
5 - Odd

Sum: 15
```

The program uses the modulo operator to check whether each number is divisible by 2 without a remainder.

## 💻 Example Output

```text
Welcome to the Pattern Generator and Number Analyzer!

1. Generate a Pattern
2. Analyze a Range of Numbers
3. Exit

Enter your choice: 1
Enter number of rows: 5

*
**
***
****
*****

Enter your choice: 2
Enter starting number: 1
Enter ending number: 5

1 - Odd
2 - Even
3 - Odd
4 - Even
5 - Odd

Sum of numbers: 15

Enter your choice: 3
Exiting the program...
```

## 🎓 Learning Outcomes

After completing this project, I learned how to:

* 🔁 Use while and for loops in Python.
* ⭐ Generate patterns using loops.
* 🔀 Apply if-else statements for decision-making.
* 🔢 Use the range function.
* ⌨️ Take and convert user input.
* ➕ Perform arithmetic calculations.
* 🧮 Check even and odd numbers.
* 🛡️ Validate user input.
* 💻 Build a menu-driven Python program.

## 🛠️ Technologies Used

* 🐍 Python 3
* 💻 Visual Studio Code
* 🐙 GitHub

## 👩‍💻 Author

**Vishakha Junjiya**

🎓 BCA Student | 🐍 Python Learner

## 📂 Project Information

**Project Name:** Pattern Generator and Number Analyzer

**Language:** Python

**Level:** Beginner

**Purpose:** Python Fundamentals Practice

## 🏁 Conclusion

This project helped me strengthen my understanding of Python loops, conditional statements, and arithmetic operations through a practical menu-driven program. It is part of my Python learning journey and portfolio.
