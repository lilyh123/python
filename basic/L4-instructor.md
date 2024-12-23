## Lesson 4: Conditional Statements (if, elif, else) in Python

Objective: 
Introduce conditional statements for decision-making in Python.

### 1. Introduction to Conditional Statements
Conditional statements allow us to make decisions in our programs. They help us execute different code blocks based on specified conditions.

###  2. The "if" Statement
The "if" statement is used to execute a block of code if a condition is True.

Example:
```python
age = 18

if age >= 18:
    print("You are an adult.")
```

### 3. The "elif" Statement
The "elif" (short for "else if") statement is used to specify multiple conditions to check.

Example:
```python
temperature = 25

if temperature > 30:
    print("It's hot outside.")
elif temperature > 20:
    print("It's a pleasant day.")
else:
    print("It's a bit chilly.")
```

### 4. The "else" Statement
The "else" statement is used to execute a block of code if the condition specified in the "if" statement is False.

Example:
```python
num = 7

if num % 2 == 0:
    print("Even")
else:
    print("Odd")
```

### 5. Nested Conditional Statements
Conditional statements can be nested inside each other to handle more complex situations.

Example:
```python
x = 10
y = 5

if x > y:
    if x % 2 == 0:
        print("x is greater and even.")
    else:
        print("x is greater and odd.")
else:
    print("y is greater.")
```

### In-Class Examples (Additional)
Example 1: Checking if a Number is Even or Odd
```python
num = 15

if num % 2 == 0:
    print(num, "is even.")
else:
    print(num, "is odd.")
```

Example 2: Determining Eligibility for Voting
```python
age = 20

if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote yet.")
```

Example 3: Checking Leap Year
```python
year = 2024

if (year % 4 == 0 and year % 100 != 0) or (year % 400 == 0):
    print(year, "is a leap year.")
else:
    print(year, "is not a leap year.")
```

Example 4: Basic Calculator
```python
num1 = float(input("Enter the first number: "))
operator = input("Enter an operator (+, -, *, /): ")
num2 = float(input("Enter the second number: "))

if operator == '+':
    result = num1 + num2
    print("Result:", result)
elif operator == '-':
    result = num1 - num2
    print("Result:", result)
elif operator == '*':
    result = num1 * num2
    print("Result:", result)
elif operator == '/':
    if num2 == 0:
        print("Error: Division by zero.")
    else:
        result = num1 / num2
        print("Result:", result)
else:
    print("Invalid operator. Please enter +, -, *, or /.")
```

Example 5: Nested Conditional Statements
```python
x = 15
y = 10

if x > y:
    if x % 5 == 0:
        print("x is greater and divisible by 5.")
    else:
        print("x is greater but not divisible by 5.")
else:
    if y % 5 == 0:
        print("y is greater and divisible by 5.")
    else:
        print("y is greater but not divisible by 5.")
```

### 6. Exercises
- Exercise 1: Write a program that checks if a number is positive, negative, or zero, and prints an appropriate message.
- Exercise 2: Create a program that asks the user for their age and prints whether they are a child, teenager, or adult based on age ranges.
- Exercise 3: Write a program that determines if a year is a leap year. Leap years are divisible by 4 but not divisible by 100, except when divisible by 400.
- Exercise 4: Implement a basic calculator that takes two numbers and an operator (+, -, *, /) as input and performs the corresponding operation.

### 7. Conclusion
In this lesson, you've learned about conditional statements in Python, including the "if," "elif," and "else" statements. These statements enable you to make decisions and execute specific code blocks based on conditions.

Practice using conditional statements to control the flow of your programs and make them more dynamic and responsive.

#### Vocabulary Words and Definitions:
- Conditional Statements: Statements that allow different code blocks to be executed based on specified conditions.
 - "if" Statement: A conditional statement used to execute a block of code if a condition is True.
 - "elif" Statement: A conditional statement used to specify multiple conditions to check after the initial "if" statement.
 - "else" Statement: A conditional statement used to execute a block of code if the condition in the "if" statement is False.
 - Nested: Placing one construct (e.g., conditional statement) inside another construct of the same kind.

---
## Homework 4: Introduction to Conditional Statements in Python

### Objective: 
The primary objective of this assignment is to introduce students to conditional statements in Python, emphasizing decision-making through the use of `if`, `elif`, and `else` statements.

#### Problem 1: Basic Conditional Statements
1. Write a Python script that prompts the user to enter an integer. Use an `if` statement to check if the number is positive, negative, or zero.

2. Extend the script to include an `else` statement. Print an appropriate message if the number is not positive.

3. Implement an `elif` statement to check if the number is equal to 0. Print a specific message if the number is zero.

#### Problem 2: Advanced Decision-Making
4. Create a program that asks the user to input their age. Use conditional statements (`if`, `elif`, `else`) to categorize their age into the following groups:
   - 0-12: Child
   - 13-19: Teenager
   - 20-59: Adult
   - 60 and above: Senior

5. Extend the program to check if the user is a teenager with the voting age (18 years old and above). If yes, print a message encouraging them to exercise their right to vote.

6. Write comments in your code to explain the purpose of each conditional statement and provide clarity on the decision-making process.

Additional Tips:
- Utilize online resources, Python documentation, and course materials to reinforce your understanding.
- Collaborate with classmates to discuss concepts and problem-solving.
- Seek assistance from your instructor or classmates if you encounter difficulties.

---

## Homework 4 Solution

Problem 1:
```python
num = int(input("Enter an integer:"))

if num > 0:
	print("positive")
if num < 0:
	print("negative")
if num == 0:
	print("zero")
```

Problem 2:
```python
if num > 0:
	print("positive")
else:
	print("not positive")
if num == 0:
	print("zero")
```

Problem 3: 
```python
if num > 0:
	print("positive")
if num < 0:
	print("not positive")
elif num == 0:
	print("number is zero")
```

Problem 4:
```python
age = int(input("enter your age:"))

if age >= 60:
	print("Senior")
elif age >= 20:
	print("Adult")
elif age >= 13:
	print("Teenager")
else:
	print("Child")
```

Problem 5:
```python
if age >= 60:
	print("Senior")
elif age >= 20:
	print("Adult")
elif age >= 13:
	print("Teenager")
	if age >= 18:
		print("Please exercise your right to vote.")
else:
	print("Child")

```
