## Lesson 3: Basic Operations and Expressions in Python

Objective: 
Teach arithmetic operations, comparison operators, and logical expressions in Python.

### 1. Introduction to Expressions
Expressions are combinations of values and operators that can be evaluated to produce results. They are fundamental in programming and allow us to perform calculations and make decisions.

###  2. Arithmetic Operations
Python supports various arithmetic operations:
- Addition (+): Adds two numbers.
- Subtraction (-): Subtracts the right operand from the left operand.
- Multiplication (\*): Multiplies two numbers.
- Division (/): Divides the left operand by the right operand.
- Modulus (%): Returns the remainder of the division.
- Exponentiation (\*\*): Raises the left operand to the power of the right operand.
- Floor Division (//): Returns the integer part of the division.

Example:
```python
result = 10 + 5  # Addition
result = 15 - 7  # Subtraction
result = 3 * 4   # Multiplication
result = 20 / 5  # Division
result = 17 % 4  # Modulus
result = 2 ** 3  # Exponentiation
result = 21 // 5 # Floor Division
```

### 3. Comparison Operators
Comparison operators allow us to compare values and produce Boolean results (True or False):
- Equal (\==): Checks if two values are equal.
- Not Equal (!=): Checks if two values are not equal.
- Greater Than (>): Checks if the left value is greater than the right value.
- Less Than (<): Checks if the left value is less than the right value.
- Greater Than or Equal To (>=): Checks if the left value is greater than or equal to the right value.
- Less Than or Equal To (<=): Checks if the left value is less than or equal to the right value.

Example 1: Integer Operation
```python
result = 10 == 5   # Equal
result = 10 != 5   # Not Equal
result = 15 > 7    # Greater Than
result = 3 < 4     # Less Than
result = 20 >= 5   # Greater Than or Equal To
result = 17 <= 4   # Less Than or Equal To
```

### 4. Logical Expressions
Logical operators allow us to combine multiple conditions:
- Logical AND (and): True if both conditions are true.
- Logical OR (or): True if at least one condition is true.
- Logical NOT (not): Inverts the result of a condition.

Example:
```python
condition1 = True
condition2 = False

result = condition1 and condition2  # Logical AND
result = condition1 or condition2   # Logical OR
result = not condition1             # Logical NOT
```

### 5. Exercises
- Exercise 1: Calculate the area of a rectangle with a length of 5 units and a width of 3 units using arithmetic operations.
- Exercise 2: Compare your age with a friend's age and print whether you are older or younger.
- Exercise 3: Write a program that checks if a given number is even (use the modulus operator).
- Exercise 4: Create a logical expression that checks if you have both ice cream and chocolate, and print whether you can make a delicious dessert.

### 6. Conclusion
In this lesson, you've learned about expressions in Python, including arithmetic operations, comparison operators, and logical expressions. These concepts are fundamental for performing calculations and making decisions in programming.

Continue practicing with different expressions to become a proficient Python programmer. Enjoy your coding journey!

#### Vocabulary Words and Definitions:
- Expressions: Combinations of values and operators that can be evaluated to produce results.
- Arithmetic Operations: Mathematical operations like addition, subtraction, multiplication, division, modulus, exponentiation, and floor division.
- Comparison Operators: Operators used to compare values and produce Boolean results, including equal, not equal, greater than, less than, greater than or equal to, and less than or equal to.
- Logical Expressions: Expressions that use logical operators (AND, OR, NOT) to combine conditions and produce Boolean results.

---
## Homework 3: Exploring Arithmetic Operations and Logical Expressions in Python

### Objective: 
The main objective of this assignment is to teach students arithmetic operations, comparison operators, and logical expressions in Python. Students will gain hands-on experience with performing calculations and making logical decisions in a programming context.

#### Problem 1: Arithmetic Operations
1. Write a Python script that defines two variables: `num1` and `num2`. Assign them any integer values of your choice.

2. Use the following arithmetic operations with `num1` and `num2`:
   - Addition
   - Subtraction
   - Multiplication
   - Division
   - Modulus (remainder of the division)

3. Print the results of each operation in a formatted manner. For example:
   - "The sum is \_\_\_\_."
   - "The difference is \_\_\_\_."
   - "The product is \_\_\_\_."
   - "The quotient is \_\_\_\_."
   - "The remainder is \_\_\_\_."

#### Problem 2: Comparison Operators and Logical Expressions
4. Extend the script to compare `num1` and `num2` using the following comparison operators:
   - Equal to (`==`)
   - Not equal to (`!=`)
   - Greater than (`>`)
   - Less than (`<`)
   - Greater than or equal to (`>=`)
   - Less than or equal to (`<=`)

5. Print the results of each comparison, indicating whether the comparison is True or False. For example:
   - "Is num1 equal to num2? True/False."
   - "Is num1 not equal to num2? True/False."
   - "Is num1 greater than num2? True/False."
   - "Is num1 less than num2? True/False."
   - "Is num1 greater than or equal to num2? True/False."
   - "Is num1 less than or equal to num2? True/False."

6. Implement a logical expression using the `and`, `or`, and `not` operators. For example:
   - "Is num1 greater than 0 and num2 less than 10? True/False."
   - "Is num1 equal to 5 or num2 equal to 8? True/False."
   - "Is not(num1 equals num2)? True/False."

Additional Tips:
- Utilize online resources, Python documentation, and course materials to reinforce your understanding.
- Collaborate with classmates to discuss concepts and problem-solving.
- Seek assistance from your instructor or classmates if you encounter difficulties.

---

## Homework 3 Solution

Problem 1:
```python
num1 = 3
num2 = 5
```

Problem 2:
```python
addition = num1 + num2
subtraction = num1 - num2
multiplication = num1 ** num2
division = num1 / num2
modulus = num1 % num2
```

Problem 3: 
```python
print("The sum is", addition)
print("The difference is", subtraction)
print("The product is", multiplication)
print("The quotient is", division)
print("The remainder is", modulus)
```

Problem 4:
```python
equal_to = num1 == num2
not_equal_to = num1 != num2
greater_than = num1 > num2
less_than = num1 < num2
greater_than_or_equal_to = num1 >= num2
less_than_or_equal_to = num1 <= num2
```

Problem 5:
```python
print("Is num1 equal to num2?", equal_to)
print("Is num1 not equal to num2?", not_equal_to)
print("Is num1 greater than num2?", greater_than)
print("Is num1 less than num2?", less_than)
print("Is num1 greater than or equal to num2?", greater_than_or_equal_to)
print("Is num1 less than or equal to num2?", less_than_or_equal_to)

```

Problem 6: 
```python
logical_and = num1 > 0 and num2 < 10
logical_or = num1 == 5 or num2 == 8
logical_not = not(num1 == num2)

print("Is num1 greater than 0 and num2 less than 10?", logical_and)
print("Is num1 equal to 5 or num2 equal to 8?", logical_or)
print("Is not(num1 equals num2)?", logical_not)
```