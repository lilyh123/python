## Lesson 2: Variables and Data Types in Python

Objective: 
Introduce the concept of variables and explore different data types in Python, such as integers, strings, floats, and booleans.

### 1. Introduction to Variables
Variables are like containers that can store different types of data. They help us work with information in our programs.

###  2. Naming Variables
- Variable names must start with a letter or underscore (_), followed by letters, numbers, or underscores.
- Variable names are case-sensitive (e.g., 'myVar' and 'myvar' are different).
- Choose descriptive variable names for clarity.
Example:
```python
my_variable = 42
name = "Alice"
is_student = True
temperature = 25.5
```

### 3. Data Types in Python
Python supports various data types:
- Integer (int): Whole numbers (e.g., 42, -10)
- Float (float): Numbers with decimal points (e.g., 3.14, -0.5)
- String (str): Text enclosed in single ('') or double ("") quotes (e.g., "Hello, Python!")
- Boolean (bool): True or False

### In-Class Examples (Additional)
Example 1: Integer Operation
```python
num1 = 10
num2 = 5

# Addition
sum_result = num1 + num2
print("Sum:", sum_result)

# Subtraction
difference_result = num1 - num2
print("Difference:", difference_result)

# Multiplication
product_result = num1 * num2
print("Product:", product_result)

# Division
quotient_result = num1 / num2
print("Quotient:", quotient_result)
```

Example 2: Float Operations
```python
pi = 3.14159
radius = 2.0

# Calculate the area of a circle
area = pi * (radius ** 2)
print("Circle Area:", area)
```

Example 3: String Operations
```python
first_name = "John"
last_name = "Doe"

# Concatenate strings
full_name = first_name + " " + last_name
print("Full Name:", full_name)

# String Length
name_length = len(full_name)
print("Name Length:", name_length)
```

Example 4: Boolean Logic
```python
is_python_fun = True
is_learning = False

# Logical AND
both_conditions = is_python_fun and is_learning
print("Both Conditions:", both_conditions)

# Logical OR
either_condition = is_python_fun or is_learning
print("Either Condition:", either_condition)

# Logical NOT
not_python_fun = not is_python_fun
print("Not Python Fun:", not_python_fun)
```
### 4. Exercises
- Exercise 1: Create a variable `my_age` and assign your age to it as an integer.
- Exercise 2: Create a variable `favorite_number` and assign your favorite number as a float.
- Exercise 3: Create a variable 'greeting' and assign it a string with a friendly greeting.
- Exercise 4: Create a variable `is_happy` and assign it a boolean value representing whether you are happy today.
- Exercise 5: Calculate the sum of two integers and store the result in a variable `total`.
- Exercise 6: Concatenate two strings to form a full name and store it in a variable `full_name`.
- Exercise 7: Calculate the average of two float numbers and store the result in a variable 'average'.

### 5. Conclusion
In this lesson, you've learned about variables and different data types in Python. Variables are essential for storing and working with data in your programs. Understanding data types helps you manage and manipulate information effectively.

Continue practicing with variables and data types to become a proficient Python programmer. Enjoy your coding journey!

#### Vocabulary Words and Definitions:
- Variables: Containers used to store data in a program.
- Data Types: Categories that classify data values, such as integers, floats, strings, and booleans.
- Integer (int): A data type for whole numbers.
- Float (float): A data type for numbers with decimal points.
- String (str): A data type for text enclosed in quotes.
- Boolean (bool): A data type with values True or False.

---
## Homework 2: Exploring Python Variables and Data Types

### Objective: 
The main objective of this assignment is to introduce students to the concept of variables and explore different data types in Python, including integers, strings, floats, and booleans. Additionally, students will become familiar with relevant programming vocabulary.

#### Problem  1: Understanding Variables and Data Types
1. Write a Python script that declares variables for the following information:
   - Your age (an integer)
   - Your full name (a string)
   - The temperature outside (a float)
   - Whether it's sunny or not (a boolean)

2. Use the `print()` function to display the values of these variables in a formatted sentence. For example:
   - "My age is \_\_\_\_."
   - "My name is \_\_\_\_."
   - "The temperature outside is ____ degrees."
   - "It is sunny: True/False."

3. In comments, explain the purpose of each variable and its corresponding data type.

#### Problem  2: Exploring Data Type Conversions
4. Create a Python script that prompts the user to enter their age using the `input()` function. Convert the input to an integer and store it in a variable.

5. Ask the user to enter a temperature in Celsius. Convert the input to a float and store it in another variable.

6. Use the `print()` function to display the user's age and the converted temperature in a formatted sentence. For example:
   - "You are ____ years old."
   - "The temperature in Celsius is ____ degrees."


Vocabulary:

1. Variable: A named storage location in a program where you can store data for later use.
2. Data Type: Specifies the type of data that a variable can store. Common data types include integers, strings, floats, and booleans.
3. Integer: A data type representing whole numbers without decimal points in Python.
4. String: A data type representing a sequence of characters (text) in Python.
5. Float: A data type representing numbers with decimal points in Python.
6. Boolean: A data type representing the binary values True or False.
7. Data Type Conversion: The process of converting a value from one data type to another, such as converting a string to an integer.


Additional Tips:
- Utilize online resources, Python documentation, and course materials to reinforce your understanding.
- Collaborate with classmates to discuss concepts and problem-solving.
- Seek assistance from your instructor or classmates if you encounter difficulties.

---

## Homework 2 Solution

Problem 1:
```python
age = 10
full_name = "Bob John"
temperature = 72.5
sunny = False
```

Problem 2:
```python
print("My age is", age)
print("My name is", full_name)
print("The temperature outside is", temperature, "degrees")
print("It is sunny:", sunny)
```

Problem 3: 
```python
age = 10 # stores the age, integer
full_name = "Bob John" # stores full name, string
temperature = 72.5 # stores temperature, float
sunny = False # stores sunny state, boolean
```

Problem 4:
```python
age = int(input("Enter your age: "))
print("You are", age, "years old.")
```

Problem 5:
```python
temperature = float(input("Enter temperature in Celsius:"))
```

Problem 6: 
```python
print("You are", age, "years old.")
print("The temperature in Celcius is", temperature, "degrees.")
```