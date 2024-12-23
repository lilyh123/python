## Lesson 8: Dictionaries and Sets in Python

Objective: 
Teach the use of dictionaries and sets for efficient data organization and retrieval.

### 1. Introduction to Dictionaries and Sets
Dictionaries and sets are data structures in Python that allow you to store and manipulate data efficiently.
- Dictionaries store data as key-value pairs, providing quick access to values based on unique keys.
- Sets store unique elements and are used for tasks like deduplication and membership testing.

###  2. Creating Dictionaries and Sets
Dictionaries are created using curly braces {} or the "dict()" constructor.
Sets are created using curly braces {} or the "set()" constructor.

Example:
```python
student = {
    "name": "Alice",
    "age": 25,
    "grade": "A"
}

colors = {"red", "green", "blue"}
```

### 3. Accessing and Modifying Dictionaries
You can access dictionary values using keys and modify them as needed.

Example:
```python
name = student["name"]
student["age"] = 26
```

### 4. Set Operations
Sets support common set operations like union, intersection, and difference.

Example:
```python
set1 = {1, 2, 3}
set2 = {3, 4, 5}

union_set = set1.union(set2)
intersection_set = set1.intersection(set2)
difference_set = set1.difference(set2)
```

### 5. Additional Examples
Example 1: Counting Character Occurrences
```python
text = "python programming"
char_count = {}

for char in text:
    if char.isalpha():
        char = char.lower()
        if char in char_count:
            char_count[char] += 1
        else:
            char_count[char] = 1

print("Character count:", char_count)
```

Example 2: Creating a Set from a List
```python
fruits_list = ["apple", "banana", "cherry", "apple"]
unique_fruits = set(fruits_list)
print("Unique fruits:", unique_fruits)
```

### 6. Exercises
- Exercise 1: Create a dictionary to store information about a book (title, author, year of publication) and print the book's details.
- Exercise 2: Given a list of numbers, create a set of unique numbers from the list.
- Exercise 3: Write a program that counts and prints the frequency of each word in a given text.

### 7. Conclusion
In this lesson, you've learned about dictionaries and sets in Python, which are essential for efficient data organization and retrieval. Dictionaries provide quick access to data using keys, while sets store unique elements and support various set operations.

Continue practicing with dictionaries and sets to optimize data manipulation in your Python programs.

#### Vocabulary Words and Definitions:
- Dictionary: A data structure that stores data as key-value pairs, allowing quick access to values using unique keys.
- Set: A data structure that stores unique elements and supports set operations like union and intersection.
- Key: A unique identifier used to access values in a dictionary.
- Value: Data associated with a key in a dictionary.
- Union: A set operation that combines two sets and returns the elements present in either or both sets.
- Intersection: A set operation that returns the common elements between two sets.
- Difference: A set operation that returns the elements present in one set but not in the other.

---
## Homework 8: Utilizing Dictionaries and Sets in Python

### Objective: 
The primary objective of this assignment is to introduce students to the concepts of dictionaries and sets in Python, emphasizing their role in efficient data organization and retrieval.

#### Problem 1: Dictionary Basics
1.  Write a Python script that defines a dictionary representing information about a person. Include the following key-value pairs:
   - Name
   - Age
   - City
   - Occupation

2. Print the entire dictionary and then print each piece of information separately using the respective keys.

3. Update one of the values in the dictionary (e.g., change the person's city) and print the modified dictionary.

#### Problem 2: Dictionary Operations
4. Create a program that simulates a basic inventory system. Define a dictionary where keys represent items (e.g., 'item1', 'item2') and values represent their quantities.

5. Implement the following operations:
   - Add a new item to the inventory.
   - Remove an item from the inventory.
   - Update the quantity of a specific item.
   - Check if a particular item is present in the inventory.

#### Problem 3: Set Operations
6. Write a Python script that initializes two sets with numerical values.

7. Perform the following set operations and print the results:
   - Union of the two sets.
   - Intersection of the two sets.
   - Difference between the two sets.

8. Use a set to remove duplicate elements from a list of numbers. Print both the original list and the list after removing duplicates.

Additional Tips:
- Utilize online resources, Python documentation, and course materials to reinforce your understanding.
- Collaborate with classmates to discuss concepts and problem-solving.
- Seek assistance from your instructor or classmates if you encounter difficulties.

---
## Homework 8 Solution

Problem 1:
```python
person = {
    "Name": "John Doe",
    "Age": 30,
    "City": "New York",
    "Occupation": "Software Engineer"
}
```

Problem 2:
```python
# Print the entire dictionary
print(person)

# Print each piece of information separately
print("Name:", person["Name"])
print("Age:", person["Age"])
print("City:", person["City"])
print("Occupation:", person["Occupation"])
```

Problem 3: 
```python
# Update the city
person["City"] = "Los Angeles"

# Print the modified dictionary
print(person)
```

Problem 4:
```python
# Define an inventory dictionary
inventory = {
    "item1": 10,
    "item2": 5,
    "item3": 20
}
```

Problem 5:
```python
# Add a new item to the inventory
inventory["item4"] = 15
print("Inventory after adding item4:", inventory)

# Remove an item from the inventory
del inventory["item2"]
print("Inventory after removing item2:", inventory)

# Update the quantity of a specific item (e.g., item1)
inventory["item1"] = 25
print("Inventory after updating item1:", inventory)

# Check if a particular item is present in the inventory
item_to_check = "item3"
if item_to_check in inventory:
    print(f"{item_to_check} is present in the inventory.")
else:
    print(f"{item_to_check} is not present in the inventory.")
```

Problem 6:
```python
# Initialize two sets with numerical values
set1 = {1, 2, 3, 4, 5}
set2 = {4, 5, 6, 7, 8}
```

Problem 7:
```python
# Union of the two sets
union_result = set1.union(set2)
print("Union of set1 and set2:", union_result)

# Intersection of the two sets
intersection_result = set1.intersection(set2)
print("Intersection of set1 and set2:", intersection_result)

# Difference between the two sets
difference_result = set1.difference(set2)
print("Difference between set1 and set2:", difference_result)
```

Problem 8:
```python
# Original list with duplicate elements
num_list = [1, 2, 3, 2, 4, 5, 1, 6, 3]

# Remove duplicates by converting the list to a set
unique_numbers = list(set(num_list))

# Print the original list and the list after removing duplicates
print("Original list:", num_list)
print("List after removing duplicates:", unique_numbers)
```