## Lesson 6: Working with Strings in Python

Objective: 
Cover string manipulation, string methods, and formatting in Python.

### 1. Introduction to Strings
Strings are sequences of characters in Python. They are used to represent text and are a fundamental data type.

### 2. Creating Strings
Strings can be created using single quotes (''), double quotes (" "), or triple quotes (''' ''') for multi-line strings.

Example:
```python
single_quoted = 'Hello, World!'
double_quoted = "Python Programming"
multi_line = '''
This is a multi-line string.
It can span across multiple lines.
'''
```

### 3. String Manipulation
- Concatenation: Combining two or more strings using the + operator.
- Repetition: Repeating a string using the * operator.

Example:
```python
first_name = "John"
last_name = "Doe"

full_name = first_name + " " + last_name
greeting = "Hello, " + full_name

repeated_text = "Repeat " * 3  # Repeats "Repeat " three times
```

### 4. String Methods
Python provides various string methods for string manipulation:
- len(): Returns the length of a string.
- lower(): Converts a string to lowercase.
- upper(): Converts a string to uppercase.
- strip(): Removes leading and trailing whitespace.
- split(): Splits a string into a list of substrings.
- join(): Joins a list of strings into one string.
- find(): Searches for a substring and returns its index.
- replace(): Replaces a substring with another string.

Example: 
```python
text = "   Python Programming   "
length = len(text)
lower_text = text.lower()
upper_text = text.upper()
stripped_text = text.strip()
word_list = text.split()
new_text = " | ".join(word_list)
index = text.find("Programming")
replaced_text = text.replace("Python", "Java")
```

### 5. String Formatting
String formatting allows you to create strings with placeholders and fill them with values.

Example:
```python
name = "Alice"
age = 30
formatted_text = f"My name is {name} and I am {age} years old."
pi = 3.14159
formatted_pi = f"Pi is approximately {pi:.2f}"  # Formatting with 2 decimal places
```

### 6. Additional Examples
Example 1: Counting Characters
```python
text = "Python is fun!"
count_e = text.count("e")
print("Number of 'e' characters:", count_e)
```

Example 2: Reversing a String
```python
text = "Python"
reversed_text = text[::-1]
print("Reversed string:", reversed_text)
```

Example 3: Checking for Substring
```python
email = "user@example.com"
if "@" in email and "." in email:
    print("Valid email address.")
else:
    print("Invalid email address.")
```

Example 4: Removing Whitespace
```python
input_text = "  This is some input text.  "
cleaned_text = input_text.strip()
print("Cleaned text:", cleaned_text)
```

### 7. Exercises
- Exercise 1: Create a program that takes a user's first name and last name as input and prints a personalized greeting.
- Exercise 2: Write a program that counts the number of vowels in a given string.
- Exercise 3: Format a message that displays the current date and time in a readable format.
- Exercise 4: Remove any leading and trailing spaces from a given string.

### 8. Conclusion
In this lesson, you've learned how to work with strings in Python, including string manipulation, string methods, and string formatting. Strings are essential for handling text data in various programming tasks.

Continue practicing with strings to become proficient in working with textual data in your Python programs.

#### Vocabulary Words and Definitions:
- String: A sequence of characters used to represent text.
- Concatenation: Combining multiple strings into one.
- Placeholder: A special symbol or syntax used to represent values that will be inserted into a string.
- Formatting: The process of creating formatted strings with placeholders.

---
## Homework 6: Exploring String Manipulation and Formatting in Python
### Objective: 
The primary objective of this assignment is to introduce students to string manipulation, various string methods, and formatting in Python. This assignment aims to enhance students' proficiency in working with text data.

#### Problem 1: Basic String Manipulation
1. Write a Python script that initializes a string variable with your full name.

2. Use string concatenation to create a new string that includes the message "Hello, my name is" followed by your full name.

3. Implement string slicing to extract and print only the first name from the full name.

#### Problem 2: String Methods
4. Create a program that prompts the user to enter a sentence using the `input()` function.

5. Use the `len()` function to calculate and print the length of the entered sentence.

6. Apply the following string methods to the entered sentence and print the results:
   - Convert the sentence to uppercase.
   - Convert the sentence to lowercase.
   - Capitalize the first letter of the sentence.
   - Count the occurrences of a specific letter or word in the sentence.
   - Check if the sentence ends with a question mark.

#### Problem 3: String Formatting
7. Write a Python script that uses string formatting to create a message containing the current date. Use the `datetime` module to obtain the current date.

8. Extend the script to include placeholders for the day, month, and year in the message. Print the formatted message.

9. Implement f-strings or the `format()` method to display a numerical calculation in a sentence. For example, "The result of 5 multiplied by 3 is \_\_\_\_.

Additional Tips:
- Utilize online resources, Python documentation, and course materials to reinforce your understanding.
- Collaborate with classmates to discuss concepts and problem-solving.
- Seek assistance from your instructor or classmates if you encounter difficulties.

---
## Homework 6 Solution

Problem 1:
```python
full_name = "John Doe"
```

Problem 2:
```python
greeting = "Hello, my name is " + full_name
print(greeting)
```

Problem 3: 
```python
first_name = full_name.split()[0]  # Split the name and take the first part
print("First name:", first_name)
```

Problem 4:
```python
sentence = input("Enter a sentence: ")
```

Problem 5:
```python
print("Length of the sentence:", len(sentence))
```

Problem 6:
```python
# Convert the sentence to uppercase
print("Uppercase:", sentence.upper())

# Convert the sentence to lowercase
print("Lowercase:", sentence.lower())

# Capitalize the first letter of the sentence
print("Capitalized:", sentence.capitalize())

# Count the occurrences of a specific letter or word (e.g., 'a')
word_count = sentence.lower().count('a')  # Case insensitive search
print("Occurrences of 'a':", word_count)

# Check if the sentence ends with a question mark
ends_with_question = sentence.endswith('?')
print("Ends with a question mark:", ends_with_question)
```

Problem 7:
```python
import datetime 

# Get the current date 
current_date = datetime.datetime.now() 
date_message = "Today's date is: {}".format(current_date.strftime('%Y-%m-%d')) print(date_message)
```

Problem 8:
```python
day = current_date.day 
month = current_date.month 
year = current_date.year
```

Problem 9:
```python
number1 = 5 
number2 = 3 
result = number1 * number2 

calculation_message = f"The result of {number1} multiplied by {number2} is {result}." print(calculation_message)
```