[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15320052&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
Python is an interpreted programming language known for its simlicity and readability. its key features include:
Dynamic typing
Comprehensive standard library
cross-platform
Extensible and embeddable
It is therefore suitable for web development in frameworks like Django and Flask e.g developing a social media website using Django
It is also suitable in data science and machine learning. For example, analyzing a dataset and building predictive models using pandas and Scikit-Learn
Python is also used in game development using libraries like Pygame, for example creating a 2D platformer game

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
Download Python installer ftom python website
Run the installer and make sure to add Python 3.12 to PATH
Follow the installation prompts to complete the set up
Verify the installation in the command prompt using the command 'python --version'
How to set up a virtual environment;
first create a virtual environment by using the command 'python -m venv myenv'
activate it by using the command 'myenv\scripts\activate'
3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
 A simple python program that prints "Hello, world" is
 print("Hello, world")
 Print is a function that displays the specific message to the scrn.
 "Hello, world" is a string argument passed to th 'print' function.
 parentheses are used to enclose the argument for the function

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
the different data types in python include;
Integer: it represents whole numbers
Float: it reresents numbers with decimal points
String: it represents a sequence of characters.
Bool: represents a 'true' or 'false' values
List- represents ordered collection of items
Tule: represents an ordered, immutable collection of items
Dictionary: represents a collection of key-value pairs
Set: represents an unordered collection of unique items.
below is how to create and use variables of differnt data types:
# integer
 age = 20
 print("Age:",age)
  print("Type of age:", tye(age))
# Float
 pi = 3.14
 print("Pi", pi)
rint("Tye of pi:", type(pi))
# string
   name = "Belinda"
   print("Name:", name)
   print("Type of name:", type(name))
   # Boolean
   is_student = True
   print("Is student:", is_student)
   print("Type of is_student:", type(is_student))
   # List
   cars = ["premio","lexus","mazda"]
   print("Cars:", cars)
   print("Type of fruits:", type(fruits))
   # Tupple
   coordinates = (12.0, 14.0)
   print("coordinates:", coordinates)
   print("Type of coordinates:", type(coordinates))
   # Dictionary
   Vehicle = {"type":"toyota", "model":"mazda" }
   print("vehicle", vehicle)
   print("Type of vehicle:", type(vehicle))
   # set
   door_numbers ={23, 45, 62}
   print("door numbers", door_numbers)
   print("Tye of door_numbers:", type(door_numbers))

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
Conditional statements and loops allow you to execute code based on certain conditions and to repeat code multiple times. For example:
age = 18

if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
fruits = ["apple", "banana", "cherry"]

The 'if' statement checks if  the condition 'age>=18' is 'True'. If it is 'True', it executes the block code under the 'if' statement. However if the condition is 'false', it executes the block of code under the 'else' statements

for fruit in fruits:
    print(fruit)
    
    The 'for' loop iterates over each item in the 'fruits' list. For each iteration, the variable 'fruit' takes the value of the current item in the list.

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
these are reusable code that perform a specific task and are defined using the 'def' keyword, followed by function name and parentheses that may include parameters. They assist in making the code organized and easy to read.
# Example of how to call the function
result = add_numbers(6, 2)
print("The sum is:", result)
7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   Curly brackets are use in dictionaries while square brackets are used in lists
   list is an ordered collection of items while dictionaries is an ordered collection of items
   in dictionaries, items are accessed by their key while in lists, items are accessed by their integer position.
   Example of both in a script: 

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
# Creating a list of numbers
numbers = [1, 2, 3, 4, 5]
print("Original list:", numbers)

# Basic operations on list
# Append a new number to the list
numbers.append(6)
print("List after appending 6:", numbers)

# Remove a number from the list
numbers.remove(3)
print("List after removing 3:", numbers)

# Accessing an item by index
print("Item at index 2:", numbers[2])

# Creating a dictionary with key-value pairs
person = {
    "name": "Alice",
    "age": 30,
    "city": "New York"
}
print("Original dictionary:", person)

# Basic operations on dictionary
# Adding a new key-value pair
person["email"] = "alice@example.com"
print("Dictionary after adding email:", person)

# Removing a key-value pair
del person["age"]
print("Dictionary after removing age:", person)

# Accessing a value by key
print("Name:", person["name"])

# Updating a value
person["city"] = "San Francisco"
print("Dictionary after updating city:", person)

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
   A module is a file cointaining ython definitions and statements. It allows organization of code into separate files thus making it easier to manage and reuse.
   Package is a way of structuring python's module namespace by usind "dotted module names"
   How to import and use a module using 'math' module;
   
import math

# Using the sqrt function to compute the square root of 16
square_root = math.sqrt(16)
print("The square root of 16 is:", square_root)

# Using the factorial function to compute the factorial of 5
factorial = math.factorial(5)
print("The factorial of 5 is:", factorial)

# Using the pi constant
pi_value = math.pi
print("The value of pi is:", pi_value)

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
# Reading from a file
try:
    with open('example.txt','r') as file:
         content = file.read
         print(content)
except FileNotFoundError:
       print("The file does not exist) 
# Writing to a fie
lines = ["First line", "Second line", "Third line"]
with open('output.txt', 'w') as file:
     for line in lines:
       file.write(line +'\n')
# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


