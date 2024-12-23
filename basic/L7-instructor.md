## Lesson 7: Loops (for and while) in Python

Objective: 
Teach the use of for and while loops for repetitive tasks and iterations in Python.

### 1. Introduction to Loops
Loops are control structures that allow you to repeat a block of code multiple times. They are essential for automating repetitive tasks and iterating over collections of data.

###  2. The "for" Loop
The "for" loop is used to iterate over a sequence (such as a list, tuple, string, or range) and execute a block of code for each element in the sequence.

Example:
```python
fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)
```

### 3. The "while" Loop
The "while" loop is used to repeatedly execute a block of code as long as a specified condition is True.

Example:
```python
count = 1

while count <= 5:
    print("Count:", count)
    count += 1
```

### 4. Loop Control Statements
Loop control statements allow you to control the flow of loops.
- "break": Terminates the loop prematurely.
- "continue": Skips the current iteration and continues to the next one.

Example:
```python
numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]

for number in numbers:
    if number % 2 == 0:
        print("Even:", number)
    else:
        continue
```

### 5. Looping with Range
The "range()" function generates a sequence of numbers, which can be used with "for" loops to specify a range of iterations.

Example:
```python
for i in range(1, 6):
    print(i)
```

### 6. Additional Examples
Example 1: Sum of Numbers
```python
total = 0

for num in range(1, 6):
    total += num

print("Sum of numbers:", total)
```

Example 2: Finding Prime Numbers
```python
prime_numbers = []

for num in range(2, 20):
    is_prime = True
    for i in range(2, num):
        if num % i == 0:
            is_prime = False
            break
    if is_prime:
        prime_numbers.append(num)

print("Prime numbers:", prime_numbers)
```

Example 3: Countdown
```python
countdown = 5

while countdown > 0:
    print("Countdown:", countdown)
    countdown -= 1
```

### 7. Exercises
- Exercise 1: Write a program that prints the multiplication table of a given number (e.g., 7 times table).
- Exercise 2: Create a program that calculates and prints the factorial of a given number.
- Exercise 3: Implement a guessing game where the user has to guess a secret number. Use a "while" loop until the correct number is guessed.

### 8. Conclusion
In this lesson, you've learned about "for" and "while" loops in Python, which are used for repetitive tasks and iterations. Loops are powerful tools for automating tasks and processing data efficiently.

Continue practicing with loops to become proficient in using them for various programming challenges.

#### Vocabulary Words and Definitions:
- Loop: A control structure that allows you to repeat a block of code multiple times.
- Iteration: Each execution of the loop's code block is called an iteration.
- Sequence: An ordered collection of elements, such as a list, tuple, string, or range.
- Loop Control Statements: Statements like "break" and "continue" that control the flow of loops.
- Range: A function that generates a sequence of numbers for use in loops.

---
## Homework 7: Mastering Loops in Python

### Objective: 
The main objective of this assignment is to familiarize students with the use of `for` and `while` loops in Python, emphasizing their role in handling repetitive tasks and iterations.

#### Problem 1: For Loops
1. Write a Python script that uses a `for` loop to print the squares of numbers from 1 to 5. The output should resemble:
```
The square of 1 is 1
The square of 2 is 4
The square of 3 is 9
The square of 4 is 16
The square of 5 is 25
```

2. Extend the script to calculate and print the sum of these squared numbers.

#### Problem 2: While Loops
3. Create a program that uses a `while` loop to print the Fibonacci sequence up to the 10th term. The Fibonacci sequence starts with 0 and 1, and each subsequent term is the sum of the two preceding terms.

4. Implement a `while` loop to prompt the user for a number. Keep prompting the user until they enter a positive number. Print a message indicating the positive number entered.

#### Problem 3: Loop Operations
5. Write a Python script that uses a `for` loop to iterate through a list of words. Print each word in uppercase.

6. Create a program that utilizes a `while` loop to calculate the factorial of a given number. The factorial of a non-negative integer is the product of all positive integers less than or equal to that number.

Additional Tips:
- Utilize online resources, Python documentation, and course materials to reinforce your understanding.
- Collaborate with classmates to discuss concepts and problem-solving.
- Seek assistance from your instructor or classmates if you encounter difficulties.

---
## Homework 7 Solution

Problem 1:
```python
for i in range(1, 6):
    print(f"The square of {i} is {i * i}")
```

Problem 2:
```python
sum = 0

for i in range(1, 6):
    print(f"The square of {i} is {i * i}")
    sum += i * i

print(f"Sum of squared numbers is {sum}")
```

Problem 3: 
```python
# Initialize the first two terms of the Fibonacci sequence
a, b = 0, 1
count = 1

# Print the Fibonacci sequence up to the 10th term using a while loop
while count <= 10:
    print(a, end=" ")
    a, b = b, a + b  # Update values for the next term
    count += 1
```

Problem 4:
```python
# While loop to keep prompting the user until a positive number is entered
while True:
    number = float(input("Enter a positive number: "))
    if number > 0:
        print(f"Thank you! You entered the positive number: {number}")
        break  # Exit the loop when a valid positive number is entered
    else:
        print("That's not a positive number. Please try again.")
```

Problem 5:
```python
words = ["hello", "world", "python", "is", "awesome"]

# For loop to print each word in uppercase
for word in words:
    print(word.upper())
```

Problem 6:
```python
# Prompt the user for a number to calculate the factorial
num = int(input("Enter a non-negative integer to calculate its factorial: "))

# Initialize the factorial variable and the counter
factorial = 1
counter = 1

# While loop to calculate the factorial
while counter <= num:
    factorial *= counter
    counter += 1

# Output the result
print(f"The factorial of {num} is {factorial}")
```