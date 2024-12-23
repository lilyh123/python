## Lesson 1: Introduction to Programming with Python

Objective: 
In this beginner-friendly tutorial, we will introduce students to the exciting world of programming using the Python programming language. We'll cover basic Python syntax and demonstrate how to use print statements and simple input/output functions.

### 1. What is Programming?
Programming is the process of giving instructions to a computer to perform specific tasks. Computers are powerful, but they are dumb. They need step-by-step instructions to do anything, and that's where programming comes in.

### 2. Why Python?
Python is an excellent language for beginners because it has a simple and readable syntax. It's widely used in various fields like web development, data analysis, artificial intelligence, and more.

### 3. Setting Up Python
Before we start coding, let's make sure you have Python installed on your computer. Visit the official Python website (https://www.python.org/downloads/) and download the latest version for your operating system.

### 4. Your First Python Program
Open a text editor (like Notepad on Windows or VSCode) and create a new file with a `.py` extension.

Let's write our first Python program:

```python
# This is a comment
print("Hello, World!")
```

- Save the file and open your terminal (command prompt on Windows).
- Navigate to the directory where you saved your Python file.
- Type `python filename.py` and press Enter.

### 5. Comments in Python
Comments begin with a `#` symbol. They are for your reference and don't affect the program's execution.

### 6. User Input and Output
You can take input from users using the `input()` function:
```python
user_input = input("Enter your name: ")
print("Hello,", user_input)
```

Here, `input()` takes user input and stores it in the `user_input` variable. We then use `print()` to display a greeting.

### Python Code Examples:
Example 1: Greeting User
```python
user_input = input("Enter your name: ")
print("Hello,", user_input)
```

Example 2: Simple Calculator
```python
num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))

sum_result = num1 + num2
difference_result = num1 - num2
product_result = num1 * num2
quotient_result = num1 / num2

print("Sum:", sum_result)
print("Difference:", difference_result)
print("Product:", product_result)
print("Quotient:", quotient_result)
```

### 7. Exercises
- Exercise 1: Modify the "Hello, World!" program to print your own custom greeting message.
- Exercise 2: Write a program that asks the user for their age and prints a message telling them how many years they have until they turn 100 years old.
- Exercise 3: Create a simple calculator program that takes two numbers as input and allows the user to perform addition, subtraction, multiplication, and division operations.

### 8. Conclusion
This is just the beginning of your programming journey with Python. You've learned about basic Python syntax, how to use print statements, and how to take user input without explicitly using variables and data types. As you continue your learning, you'll explore more complex concepts and build exciting applications.

Stay curious, practice coding, and you'll become a proficient Python programmer in no time!

#### Vocabulary Words and Definitions:
- Programming: The process of giving instructions to a computer to perform specific tasks.
- Python: A high-level programming language known for its simplicity and readability.
- Syntax: The set of rules that dictate how programs written in a particular programming language should be structured.
- Comment: An annotation within the code that is not executed and is used for documentation and explanation.
- Variable: A container used to store data.
- Input: Data provided to a program from an external source, such as the user.
- Output: The result or data produced by a program.
- Data Types: Categories that classify data values, such as integers, floats, strings, and booleans.

---
## Homework 1: Introduction to Programming with Python
### Objective: 
The primary goal of this assignment is to provide students with a foundational understanding of programming using Python. This assignment focuses on basic Python syntax, the usage of print statements, and simple input/output functions. Additionally, it incorporates relevant programming vocabulary to reinforce understanding.

#### Task 1: Python Basics and Vocabulary
1. Write a Python script that uses the `print()` function to display the phrase "Hello, _______!" where the blank is filled in with a variable containing your name.

2. Create a variable named score and assign it the value 0. Use the `print()` function to display the content of the variable.

3. Explain in a comment what the term "variable" means in programming and provide an example in your code.

#### Task 2: Input and Output Functions
4. Write a Python script that takes the user's age as input using the `input()` function and prints a message like "You are \_\_\_\_ years old," replacing the blank with the user's input.

5. Create a program that prompts the user to enter their favorite color using the `input()` function. Display a message using `print()` that incorporates their favorite color.

6. Define the term "input function" in programming within a comment in your code. Include an example demonstrating the usage of the `input()` function.

Programming Vocabulary:
- Variable
- Input Function
- Conditional Statement
- Comment
- Syntax

Additional Tips:
- Utilize online resources, Python documentation, and course materials to reinforce your understanding.
- Collaborate with classmates to discuss concepts and problem-solving.
- Seek assistance from your instructor or classmates if you encounter difficulties.

---

## Homework 1 Solution

Problem 1:
```python
print("Hello, Bob!")
```

Problem 2:
```python
score = 0
print(score) # or print("Score:", score)
```

Problem 3: 
A variable is like a container used to store data.
```python
name = "Bob"
```

Problem 4:
```python
age = input("Enter your age: ")
print("You are", age, "years old.")
```

Problem 5:
```python
favorite_color = input("Enter your favorite color:")
print("Your favorite color is:", favorite_color)
```

Problem 6: 
```python
# The input function allows the program to prompt the user to enter something in the console.

# Example:
name = input("Enter your name:")
print("Your name is:", name)
```