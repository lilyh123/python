## Lesson 5: Lists and Tuples in Python

Objective: 
Introduce lists and tuples, their properties, manipulation, and indexing.

### 1. Introduction to Lists and Tuples
Lists and tuples are data structures in Python that allow you to store collections of values.
- Lists are mutable, meaning their elements can be changed after creation.
- Tuples are immutable, meaning their elements cannot be changed after creation.

### 2. Creating Lists and Tuples
Lists are created using square brackets \[\].
Tuples are created using parentheses ().

Example:
```python
fruits_list = ["apple", "banana", "cherry"]
colors_tuple = ("red", "green", "blue")
```

### 3. Accessing Elements
Elements in lists and tuples are accessed using indexing.

Example:
```python
first_fruit = fruits_list[0]
second_color = colors_tuple[1]
```

### 4. Manipulating Lists (Mutable)
- Adding elements: Use the append() method to add elements to the end of a list.
- Removing elements: Use the remove() method to remove a specific element by value.
- Modifying elements: Assign a new value to an element using indexing.

Example: 
```python
fruits_list.append("orange")  # Adding an element
fruits_list.remove("banana")  # Removing an element
fruits_list[1] = "grape"      # Modifying an element
```

### 5. Manipulating Tuples (Immutable)
Tuples cannot be modified after creation, so all elements must be defined when creating the tuple.

Example:
```python
coordinates = (3, 4)
```

### 6. Additional Examples
Example 1: Slicing Lists
```python
numbers_list = [1, 2, 3, 4, 5]
sliced_list = numbers_list[1:4]  # Slice from index 1 to 3 (exclusive)
print(sliced_list)
```

Example 2: Concatenating Lists
```python
list1 = [1, 2, 3]
list2 = [4, 5, 6]
combined_list = list1 + list2
print(combined_list)
```

Example 3: Tuple Unpacking
```python
coordinates = (5, 7)
x, y = coordinates
print("x =", x)
print("y =", y)
```

Example 4: Finding the Length
```python
num_list = [10, 20, 30, 40, 50]
length = len(num_list)
print("Length of num_list:", length)
```

 Example 5: Checking for Existence
```python
fruits = ["apple", "banana", "cherry"]
if "banana" in fruits:
    print("Banana is in the list.")
else:
    print("Banana is not in the list.")
```

### 7. Exercises
- Exercise 1: Create a list of your favorite movies. Print the first and last movies in the list.
- Exercise 2: Create a tuple with the coordinates (latitude, longitude) of your current location. Print both coordinates.
- Exercise 3: Given a list of numbers, find and print the maximum and minimum values in the list.
- Exercise 4: Write a program that takes a list of numbers, squares each number, and stores the results in a new list.

### 8. Conclusion
In this lesson, you've learned about lists and tuples in Python. Lists are mutable, while tuples are immutable. You can access elements, manipulate them, and perform various operations to work with collections of data.

Practice using lists and tuples to store and manipulate data effectively in your programs.

#### Vocabulary Words and Definitions:
- Lists: Mutable data structures in Python used to store collections of values.
- Tuples: Immutable data structures in Python used to store collections of values.
- Indexing: The process of accessing elements in a list or tuple using their position.
- Mutable: Data structures that can be modified after creation.
- Immutable: Data structures that cannot be modified after creation.

---
## Homework 5: Lists and Tuples in Python

#### Part 1: Theory Questions
1. Define the following terms:
   - List
   - Tuple
   - Indexing
   - Mutability
   - Immutability

2. Explain the difference between lists

3. Describe how indexing works in lists and tuples. Provide examples to illustrate indexing in both data structures.

#### Part 2: Coding Problems
4. Problem 1: List Manipulation
   Write a Python program that demonstrates various operations on lists, including:
   - Creating a list of integers.
   - Appending new elements to the list.
   - Removing elements from the list.
   - Accessing and modifying elements at specific indices.
   - Printing the final list.

5. Problem 2: Tuple Operations
   Write a Python program that showcases the use of tuples by performing the following operations:
   - Creating a tuple of strings.
   - Accessing elements using indexing.
   - Attempting to modify an element (which should result in an error due to immutability).
   - Concatenating two tuples.
   - Printing the final tuples.

6. Problem 3: List vs. Tuple
   Write a short essay comparing and contrasting lists and tuples in Python. Discuss their similarities, differences, and situations where one might be preferred over the other.

Submission Guidelines:
- Write your answers to the theory questions in clear and concise sentences.
- For the coding problems, write Python code that follows proper syntax and includes comments to explain the logic where necessary.
- Submit your homework as a Python script (.py file) along with your answers to the theory questions.
- Make sure your code is properly formatted and easy to read.

Note: Feel free to refer to your class notes, the lesson materials, or online resources to help you complete the homework. Good luck!

---
## Homework 5 Solution

Problem 1:
- Lists: Mutable data structures in Python used to store collections of values.
- Tuples: Immutable data structures in Python used to store collections of values.
- Indexing: The process of accessing elements in a list or tuple using their position.
- Mutable: Data structures that can be modified after creation.
- Immutable: Data structures that cannot be modified after creation.

Problem 2:
- Lists are mutable, meaning their elements can be changed (added, removed, or modified).
- Tuples are immutable, meaning once created, their elements cannot be changed.
- Use lists when you need a collection of items that can be modified (e.g., appending data).
- Use tuples for fixed collections of items that shouldn't be altered (e.g., coordinates or configuration settings). Tuples are also faster and use less memory than lists.

Problem 3: 
- Indexing in both lists and tuples works similarly: elements are accessed by their position (or index) in the collection. In Python, both lists and tuples are zero-indexed, meaning the first element is at index 0.
- List Example:
```python
my_list = [10, 20, 30, 40, 50] 

# Accessing elements using positive indices
print(my_list[0]) # Output: 10 (first element)
```
- Tuple Example:
```python
my_tuple = ('apple', 'banana', 'cherry', 'date') 

# Accessing elements by positive
index print(my_tuple[0]) # Output: 'apple'
```

Problem 4:
```python
# Creating a list of integers
my_list = [10, 20, 30, 40, 50]

# Appending new elements to the list
my_list.append(60)  # Add 60 to the end of the list
my_list.append(70)  # Add 70 to the end of the list

# Removing elements from the list
my_list.remove(20)  # Removes the first occurrence of 20
my_list.pop()       # Removes the last element (70)
my_list.pop(2)      # Removes the element at index 2 (40)

# Accessing and modifying elements at specific indices
print("Element at index 0:", my_list[0])  # Accessing element at index 0 (should be 10)
my_list[1] = 100  # Modifying the element at index 1 (change 30 to 100)

# Final List
print("\nFinal List:", my_list)
```

Problem 5:
```python
# Creating a tuple of strings
my_tuple = ('apple', 'banana', 'cherry', 'date')

# Accessing elements using indexing
print("Element at index 0:", my_tuple[0])  # Accessing the first element ('apple')
print("Element at index 2:", my_tuple[2])  # Accessing the third element ('cherry')

# Attempting to modify an element (will raise an error)
try:
    my_tuple[1] = 'blueberry'  # Attempt to modify the second element
except TypeError as e:
    print("\nError:", e)  # It will print a TypeError because tuples are immutable

# Concatenating two tuples
another_tuple = ('elderberry', 'fig', 'grape')
concatenated_tuple = my_tuple + another_tuple  # Concatenating tuples

# Printing the final tuples
print("\nOriginal Tuple:", my_tuple)
print("Another Tuple:", another_tuple)
print("Concatenated Tuple:", concatenated_tuple)
```

Problem 6: 
Lists and tuples are both ordered collections in Python, but **lists** are mutable (can be modified), while **tuples** are immutable (cannot be changed after creation). Lists are preferred when you need to modify the collection, while tuples are more efficient in terms of memory and performance when the data should remain constant. Use lists for dynamic data and tuples for fixed, unchanging data or as dictionary keys.