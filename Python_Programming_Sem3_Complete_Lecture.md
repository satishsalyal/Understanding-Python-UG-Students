<div align="center">

# 📘 Bachelor's Degree Programme in Data Science and Artificial Intelligence

## Semester-3rd (Batch: 2026-30)

### Major: Python Programming

**Course Code:** `UGMJIT3001` | **Credits:** 4 | **Max Marks:** 100

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white&style=for-the-badge)](https://jupyter.org/)
[![Data Science](https://img.shields.io/badge/Data%20Science-FF6F00?logo=databricks&logoColor=white&style=for-the-badge)](https://www.anaconda.com/)
[![AI](https://img.shields.io/badge/Artificial%20Intelligence-8E44AD?style=for-the-badge)](https://openai.com/)

</div>

---

## 📑 Table of Contents

1. [Course Overview](#1-course-overview)
2. [Unit-I: Introduction to Python Programming](#2-unit-i-introduction-to-python-programming)
3. [Unit-II: Control Structures and Functions](#3-unit-ii-control-structures-and-functions)
4. [Unit-III: Data Structures in Python](#4-unit-iii-data-structures-in-python)
5. [Unit-IV: File Handling and Introduction to Libraries](#5-unit-iv-file-handling-and-introduction-to-libraries)
6. [Course Outcomes (COs)](#6-course-outcomes-cos)
7. [Examination Pattern](#7-examination-pattern)
8. [Practice Questions](#8-practice-questions)
9. [Suggested Readings](#9-suggested-readings)

---

## 1. Course Overview

### Course Objective

> This course aims to introduce students to the **fundamentals of Python programming**. It focuses on developing problem-solving skills, understanding basic programming constructs, and enabling students to write simple programs for real-world applications.

### Marks Distribution

| Component | Marks |
|-----------|-------|
| 📝 **University Examination (Theory)** | 60 |
| 📊 **Internal Assessment** | 25 |
| 🔬 **Practical** | 15 |
| **Total** | **100** |

### Minimum Passing Marks

| Component | Minimum Marks Required |
|-----------|----------------------|
| University Examination | 24 out of 60 (40%) |
| Internal Assessment | 10 out of 25 (40%) |
| Practical | 6 out of 15 (40%) |

---

## 2. Unit-I: Introduction to Python Programming

> **Weightage:** ~15 Marks | **Lectures:** 12-14

---

### 2.1 Introduction to Programming and Python

#### What is Programming?
Programming is the process of creating a set of instructions that tell a computer how to perform a task. These instructions are written in a **programming language** that the computer can understand and execute.

#### Why Python?
Python is a high-level, interpreted, general-purpose programming language created by **Guido van Rossum** in 1991. It is one of the most popular languages for beginners and professionals alike.

| Feature | Description |
|---------|-------------|
| 🐍 **Simple Syntax** | Reads like English — easy to learn |
| 🔄 **Interpreted** | No compilation needed — run directly |
| 🧬 **Object-Oriented** | Supports OOP concepts |
| 📚 **Rich Libraries** | Thousands of built-in and third-party libraries |
| 💻 **Cross-Platform** | Runs on Windows, macOS, Linux |
| 🤖 **AI/ML Ready** | Preferred language for Data Science and AI |

#### Applications of Python

| Domain | Examples |
|--------|----------|
| 🌐 **Web Development** | Django, Flask, FastAPI |
| 📊 **Data Science** | Pandas, NumPy, Matplotlib |
| 🤖 **Machine Learning** | TensorFlow, PyTorch, Scikit-learn |
| 🎮 **Game Development** | Pygame |
| 🔒 **Cybersecurity** | Penetration testing tools |
| 📡 **IoT** | Raspberry Pi, MicroPython |
| 💰 **Finance** | Algorithmic trading, financial modeling |

---

### 2.2 Installation of Python and Working with IDEs

#### Installing Python

**Step 1:** Visit [https://www.python.org/downloads/](https://www.python.org/downloads/)

**Step 2:** Download the latest Python 3.x installer for your OS.

**Step 3:** Run the installer:
- ✅ **Windows:** Check "Add Python to PATH" before installing.
- 🍎 **macOS:** Use the `.pkg` installer or Homebrew: `brew install python`
- 🐧 **Linux:** `sudo apt install python3 python3-pip`

**Step 4:** Verify installation:
```bash
python --version
```

#### Integrated Development Environments (IDEs)

| IDE | Description | Best For |
|-----|-------------|----------|
| 🐍 **IDLE** | Python's built-in IDE | Absolute beginners |
| 📓 **Jupyter Notebook** | Interactive web-based notebook | Data Science, experimentation |
| 💻 **VS Code** | Lightweight, extensible editor | General development |
| 🛠️ **PyCharm** | Full-featured Python IDE | Large projects |
| 🕸️ **Google Colab** | Cloud-based Jupyter environment | Collaborative work |

#### Working with IDLE

```python
# IDLE is Python's default IDE
# Open IDLE -> File -> New File -> Write code -> Run -> Run Module (F5)

print("Hello, World!")
```

#### Working with Jupyter Notebook

```bash
# Install Jupyter
pip install jupyter

# Launch
jupyter notebook
```

In Jupyter, you write code in **cells** and execute them with `Shift + Enter`.

---

### 2.3 Basic Syntax and Structure

#### Python Program Structure

```python
# This is a comment
"""
This is a
multi-line comment (docstring)
"""

# Import statements
import math

# Main code
print("Welcome to Python Programming")
```

#### Indentation
Python uses **indentation** (whitespace) to define blocks of code instead of braces `{}`.

```python
# Correct indentation
if True:
    print("This is indented")      # 4 spaces (standard)
    print("Same block")

# Incorrect indentation will raise IndentationError
if True:
print("Not indented")  # Error!
```

---

### 2.4 Keywords and Identifiers

#### Python Keywords
Keywords are reserved words with special meanings. You **cannot** use them as variable names.

```python
import keyword
print(keyword.kwlist)
```

**Complete list of Python 3.x Keywords:**

| Category | Keywords |
|----------|----------|
| **Value Keywords** | `True`, `False`, `None` |
| **Operator Keywords** | `and`, `or`, `not`, `in`, `is` |
| **Control Flow** | `if`, `elif`, `else`, `for`, `while`, `break`, `continue`, `pass` |
| **Functions/Classes** | `def`, `return`, `lambda`, `yield`, `class` |
| **Exception Handling** | `try`, `except`, `finally`, `raise`, `assert` |
| **Context Managers** | `with`, `as` |
| **Others** | `import`, `from`, `global`, `nonlocal`, `del` |

#### Identifiers
An identifier is a name given to variables, functions, classes, etc.

**Rules for Identifiers:**
1. Can contain letters (a-z, A-Z), digits (0-9), and underscore (_)
2. **Cannot** start with a digit
3. **Cannot** be a keyword
4. Case-sensitive (`Name` and `name` are different)
5. No special characters (!, @, #, $, %, etc.)

```python
# Valid identifiers
name = "Alice"
_age = 25
student1 = "Bob"
_total_marks = 95

# Invalid identifiers
# 1student = "Charlie"    # Starts with digit
# my-name = "Dave"        # Contains hyphen
# class = "ECE"           # Keyword
# my name = "Eve"         # Contains space
```

---

### 2.5 Variables and Data Types

#### Variables
A variable is a named container that stores data. In Python, you **do not** need to declare the type — it is inferred automatically.

```python
# Variable assignment
name = "Alice"      # String
age = 20            # Integer
height = 5.6        # Float
is_student = True   # Boolean
```

#### Python Data Types

| Data Type | Description | Example |
|-----------|-------------|---------|
| `int` | Integer (whole numbers) | `x = 10` |
| `float` | Decimal numbers | `y = 3.14` |
| `complex` | Complex numbers | `z = 3 + 4j` |
| `str` | Text (string) | `name = "Python"` |
| `bool` | Boolean (True/False) | `flag = True` |
| `list` | Ordered, mutable collection | `lst = [1, 2, 3]` |
| `tuple` | Ordered, immutable collection | `tup = (1, 2, 3)` |
| `set` | Unordered, unique collection | `s = {1, 2, 3}` |
| `dict` | Key-value pairs | `d = {"a": 1}` |

```python
# Checking data types
x = 10
print(type(x))        # <class 'int'>

y = 3.14
print(type(y))        # <class 'float'>

name = "Python"
print(type(name))     # <class 'str'>

flag = True
print(type(flag))     # <class 'bool'>
```

#### Type Conversion (Type Casting)

```python
# Implicit conversion
x = 5       # int
y = 2.5     # float
z = x + y   # z becomes 7.5 (float)

# Explicit conversion
a = int(3.7)        # 3
b = float(5)        # 5.0
c = str(100)        # "100"
d = int("50")       # 50
e = list("abc")     # ['a', 'b', 'c']
```

---

### 2.6 Input and Output Operations

#### `print()` Function
The `print()` function displays output to the console.

```python
# Basic print
print("Hello, World!")

# Multiple values
print("Name:", "Alice", "Age:", 20)

# Using sep parameter
print("2026", "08", "18", sep="-")   # 2026-08-18

# Using end parameter
print("Hello", end=" ")
print("World")                        # Hello World

# Formatted output using f-strings (Python 3.6+)
name = "Alice"
age = 20
print(f"My name is {name} and I am {age} years old.")

# Using format()
print("My name is {} and I am {} years old.".format(name, age))

# Using % formatting (older style)
print("My name is %s and I am %d years old." % (name, age))
```

#### `input()` Function
The `input()` function reads a line of text from the user.

```python
# Basic input (returns string)
name = input("Enter your name: ")
print("Hello,", name)

# Input with type conversion
age = int(input("Enter your age: "))
print("You will be", age + 1, "next year.")

# Float input
height = float(input("Enter your height in meters: "))
print("Your height is", height, "meters")

# Multiple inputs
x, y = input("Enter two numbers separated by space: ").split()
x = int(x)
y = int(y)
print("Sum:", x + y)
```

---

### 2.7 Operators in Python

#### 1. Arithmetic Operators

| Operator | Name | Example | Result |
|----------|------|---------|--------|
| `+` | Addition | `5 + 3` | `8` |
| `-` | Subtraction | `5 - 3` | `2` |
| `*` | Multiplication | `5 * 3` | `15` |
| `/` | Division | `5 / 2` | `2.5` |
| `//` | Floor Division | `5 // 2` | `2` |
| `%` | Modulus (Remainder) | `5 % 2` | `1` |
| `**` | Exponentiation | `2 ** 3` | `8` |

```python
a = 17
b = 5

print(a + b)    # 22
print(a - b)    # 12
print(a * b)    # 85
print(a / b)    # 3.4
print(a // b)   # 3
print(a % b)    # 2
print(a ** b)   # 1419857
```

#### 2. Comparison (Relational) Operators

| Operator | Meaning | Example | Result |
|----------|---------|---------|--------|
| `==` | Equal to | `5 == 5` | `True` |
| `!=` | Not equal to | `5 != 3` | `True` |
| `>` | Greater than | `5 > 3` | `True` |
| `<` | Less than | `5 < 3` | `False` |
| `>=` | Greater than or equal | `5 >= 5` | `True` |
| `<=` | Less than or equal | `5 <= 3` | `False` |

```python
x = 10
y = 20

print(x == y)   # False
print(x != y)   # True
print(x > y)    # False
print(x < y)    # True
print(x >= 10)  # True
print(x <= 5)   # False
```

#### 3. Assignment Operators

| Operator | Example | Equivalent to |
|----------|---------|---------------|
| `=` | `x = 5` | `x = 5` |
| `+=` | `x += 3` | `x = x + 3` |
| `-=` | `x -= 3` | `x = x - 3` |
| `*=` | `x *= 3` | `x = x * 3` |
| `/=` | `x /= 3` | `x = x / 3` |
| `//=` | `x //= 3` | `x = x // 3` |
| `%=` | `x %= 3` | `x = x % 3` |
| `**=` | `x **= 3` | `x = x ** 3` |

```python
x = 10
x += 5      # x = 15
x -= 3      # x = 12
x *= 2      # x = 24
x /= 4      # x = 6.0
```

#### 4. Logical Operators

| Operator | Description | Example | Result |
|----------|-------------|---------|--------|
| `and` | True if both are True | `True and False` | `False` |
| `or` | True if at least one is True | `True or False` | `True` |
| `not` | Reverses the result | `not True` | `False` |

```python
x = 5
print(x > 3 and x < 10)   # True
print(x > 3 or x > 10)    # True
print(not(x > 3))         # False
```

#### 5. Bitwise Operators

| Operator | Name | Description |
|----------|------|-------------|
| `&` | AND | Sets each bit to 1 if both bits are 1 |
| `\|` | OR | Sets each bit to 1 if one of two bits is 1 |
| `^` | XOR | Sets each bit to 1 if only one of two bits is 1 |
| `~` | NOT | Inverts all the bits |
| `<<` | Left Shift | Shift left by pushing zeros |
| `>>` | Right Shift | Shift right by pushing copies of the leftmost bit |

```python
a = 5     # 0101 in binary
b = 3     # 0011 in binary

print(a & b)    # 1  (0001)
print(a | b)    # 7  (0111)
print(a ^ b)    # 6  (0110)
print(~a)       # -6 (inverted)
print(a << 1)   # 10 (1010)
print(a >> 1)   # 2  (0010)
```

#### 6. Membership Operators

| Operator | Description | Example |
|----------|-------------|---------|
| `in` | Returns True if value is found | `"a" in "apple"` -> `True` |
| `not in` | Returns True if value is NOT found | `"z" not in "apple"` -> `True` |

```python
fruits = ["apple", "banana", "cherry"]
print("apple" in fruits)       # True
print("grape" not in fruits)   # True
```

#### 7. Identity Operators

| Operator | Description | Example |
|----------|-------------|---------|
| `is` | True if both variables are the same object | `x is y` |
| `is not` | True if both variables are NOT the same object | `x is not y` |

```python
x = [1, 2, 3]
y = [1, 2, 3]
z = x

print(x is y)       # False (different objects)
print(x is z)       # True (same object)
print(x == y)       # True (same values)
```

#### Operator Precedence (Highest to Lowest)

| Priority | Operators |
|----------|-----------|
| 1 | `()` — Parentheses |
| 2 | `**` — Exponentiation |
| 3 | `+x`, `-x`, `~x` — Unary |
| 4 | `*`, `/`, `//`, `%` — Multiplication/Division |
| 5 | `+`, `-` — Addition/Subtraction |
| 6 | `<<`, `>>` — Bitwise shifts |
| 7 | `&` — Bitwise AND |
| 8 | `^` — Bitwise XOR |
| 9 | `\|` — Bitwise OR |
| 10 | `==`, `!=`, `>`, `<`, `>=`, `<=` — Comparisons |
| 11 | `not` — Logical NOT |
| 12 | `and` — Logical AND |
| 13 | `or` — Logical OR |
| 14 | `=`, `+=`, `-=` — Assignment |

---

## 3. Unit-II: Control Structures and Functions

> **Weightage:** ~15 Marks | **Lectures:** 12-14

---

### 3.1 Decision Making Statements

Decision-making statements allow the program to execute different blocks of code based on conditions.

#### 1. `if` Statement
Executes a block of code **only if** the condition is True.

```python
age = 18

if age >= 18:
    print("You are eligible to vote.")
```

#### 2. `if-else` Statement
Executes one block if the condition is True, another if False.

```python
age = 16

if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are NOT eligible to vote.")
```

#### 3. `if-elif-else` Statement
Checks multiple conditions in sequence.

```python
marks = 85

if marks >= 90:
    grade = "A"
elif marks >= 80:
    grade = "B"
elif marks >= 70:
    grade = "C"
elif marks >= 60:
    grade = "D"
else:
    grade = "F"

print(f"Your grade is: {grade}")
```

#### 4. Nested `if` Statements
An `if` statement inside another `if` statement.

```python
age = 25
has_license = True

if age >= 18:
    if has_license:
        print("You can drive.")
    else:
        print("You need a license to drive.")
else:
    print("You are too young to drive.")
```

#### 5. Short-Hand `if` (Ternary Operator)

```python
# Syntax: value_if_true if condition else value_if_false

age = 20
status = "Adult" if age >= 18 else "Minor"
print(status)   # Adult

# Another example
a = 10
b = 20
max_val = a if a > b else b
print(max_val)  # 20
```

---

### 3.2 Looping Constructs

Loops are used to execute a block of code repeatedly.

#### 1. `for` Loop
Iterates over a sequence (list, tuple, string, range, etc.).

```python
# Loop through a list
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)

# Loop through a string
for char in "Python":
    print(char)

# Using range()
for i in range(5):
    print(i)        # 0, 1, 2, 3, 4

# range(start, stop, step)
for i in range(1, 10, 2):
    print(i)        # 1, 3, 5, 7, 9

# Loop through a dictionary
student = {"name": "Alice", "age": 20, "grade": "A"}
for key, value in student.items():
    print(f"{key}: {value}")
```

#### 2. `while` Loop
Executes as long as a condition is True.

```python
# Basic while loop
count = 0
while count < 5:
    print(count)
    count += 1

# While with else
i = 1
while i <= 5:
    print(i)
    i += 1
else:
    print("Loop completed!")
```

#### 3. `for` vs `while` Loop

| Aspect | `for` Loop | `while` Loop |
|--------|-----------|--------------|
| Use Case | Known number of iterations | Unknown number of iterations |
| Condition | Iterates over a sequence | Checks a boolean condition |
| Example | `for i in range(10)` | `while user_input != "quit"` |

---

### 3.3 Nested Loops

A loop inside another loop.

```python
# Nested for loop - Multiplication table
for i in range(1, 6):
    for j in range(1, 6):
        print(f"{i} x {j} = {i*j}")
    print("---")

# Nested loop - Pattern printing
for i in range(1, 6):
    for j in range(i):
        print("*", end=" ")
    print()
```

---

### 3.4 Loop Control Statements

#### 1. `break` Statement
Terminates the loop immediately.

```python
for i in range(10):
    if i == 5:
        break
    print(i)    # Prints 0, 1, 2, 3, 4
```

#### 2. `continue` Statement
Skips the current iteration and moves to the next.

```python
for i in range(10):
    if i % 2 == 0:
        continue
    print(i)    # Prints only odd numbers: 1, 3, 5, 7, 9
```

#### 3. `pass` Statement
Does nothing — used as a placeholder.

```python
for i in range(5):
    if i == 3:
        pass        # TODO: handle this case later
    print(i)

# Used in empty functions/classes
def my_function():
    pass            # Will implement later

class MyClass:
    pass
```

#### Summary of Loop Control Statements

| Statement | Action | Use Case |
|-----------|--------|----------|
| `break` | Exit loop completely | Found what you're looking for |
| `continue` | Skip to next iteration | Skip invalid/unnecessary items |
| `pass` | Do nothing | Placeholder for future code |

---

### 3.5 Functions

A function is a reusable block of code that performs a specific task.

#### 1. Defining and Calling a Function

```python
# Function definition
def greet():
    print("Hello, welcome to Python!")

# Function call
greet()
greet()
```

#### 2. Function with Parameters

```python
def greet_user(name):
    print(f"Hello, {name}!")

greet_user("Alice")
greet_user("Bob")
```

#### 3. Function with Return Value

```python
def add_numbers(a, b):
    return a + b

result = add_numbers(5, 3)
print(result)   # 8
```

#### 4. Types of Arguments

```python
def student_info(name, age, grade="A"):
    print(f"Name: {name}, Age: {age}, Grade: {grade}")

# Positional arguments
student_info("Alice", 20)

# Keyword arguments
student_info(name="Bob", age=22, grade="B")

# Default argument
student_info("Charlie", 19)     # Uses default grade="A"

# Arbitrary arguments (*args)
def sum_all(*numbers):
    return sum(numbers)

print(sum_all(1, 2, 3, 4, 5))   # 15

# Arbitrary keyword arguments (**kwargs)
def display_info(**kwargs):
    for key, value in kwargs.items():
        print(f"{key}: {value}")

display_info(name="Alice", age=20, city="Delhi")
```

#### 5. Types of Functions

| Type | Description | Example |
|------|-------------|---------|
| **Built-in** | Pre-defined in Python | `print()`, `len()`, `type()`, `sum()` |
| **User-defined** | Created by the programmer | `def my_func():` |
| **Lambda** | Anonymous single-expression | `lambda x: x**2` |
| **Recursive** | Calls itself | Factorial, Fibonacci |

#### 6. Lambda Functions

```python
# Syntax: lambda arguments: expression

square = lambda x: x ** 2
print(square(5))    # 25

# Lambda with map()
numbers = [1, 2, 3, 4, 5]
squared = list(map(lambda x: x**2, numbers))
print(squared)      # [1, 4, 9, 16, 25]

# Lambda with filter()
evens = list(filter(lambda x: x % 2 == 0, numbers))
print(evens)        # [2, 4]
```

#### 7. Recursive Functions

```python
# Factorial using recursion
def factorial(n):
    if n == 0 or n == 1:
        return 1
    return n * factorial(n - 1)

print(factorial(5))     # 120
```

#### 8. Scope of Variables

```python
global_var = 10     # Global variable

def my_function():
    local_var = 5   # Local variable
    print(global_var)   # Can access global
    print(local_var)    # Can access local

my_function()
# print(local_var)    # Error! local_var is not accessible here
```

---

## 4. Unit-III: Data Structures in Python

> **Weightage:** ~15 Marks | **Lectures:** 12-14

---

### 4.1 Lists

A **list** is an ordered, mutable (changeable), and indexed collection of items.

#### Creating Lists

```python
# Empty list
my_list = []
my_list = list()

# List with values
fruits = ["apple", "banana", "cherry"]
mixed = [1, "hello", 3.14, True, [1, 2, 3]]

# List from range
numbers = list(range(1, 6))     # [1, 2, 3, 4, 5]
```

#### Accessing List Elements

```python
fruits = ["apple", "banana", "cherry", "date", "elderberry"]

# Indexing (0-based)
print(fruits[0])      # apple
print(fruits[-1])     # elderberry (last element)
print(fruits[-2])     # date (second last)

# Slicing [start:stop:step]
print(fruits[1:4])    # ['banana', 'cherry', 'date']
print(fruits[:3])     # ['apple', 'banana', 'cherry']
print(fruits[2:])     # ['cherry', 'date', 'elderberry']
print(fruits[::2])    # ['apple', 'cherry', 'elderberry']
print(fruits[::-1])   # Reversed list
```

#### List Operations

```python
# Concatenation
list1 = [1, 2, 3]
list2 = [4, 5, 6]
combined = list1 + list2    # [1, 2, 3, 4, 5, 6]

# Repetition
repeated = [0] * 5          # [0, 0, 0, 0, 0]

# Membership
print(3 in list1)           # True
print(10 not in list1)      # True

# Length
print(len(list1))           # 3
```

#### List Methods

```python
fruits = ["apple", "banana"]

# Adding elements
fruits.append("cherry")         # ['apple', 'banana', 'cherry']
fruits.insert(1, "avocado")     # ['apple', 'avocado', 'banana', 'cherry']
fruits.extend(["date", "fig"])  # Adds multiple items

# Removing elements
fruits.remove("banana")         # Removes first occurrence
popped = fruits.pop()           # Removes and returns last item
popped = fruits.pop(1)          # Removes item at index 1
fruits.clear()                  # Removes all items

# Other methods
numbers = [3, 1, 4, 1, 5, 9, 2]
numbers.sort()                  # Sorts in place: [1, 1, 2, 3, 4, 5, 9]
numbers.sort(reverse=True)      # Descending order
numbers.reverse()               # Reverses in place

print(numbers.count(1))         # 2 (counts occurrences)
print(numbers.index(5))         # Index of first occurrence of 5

# Copying a list
new_list = numbers.copy()
new_list = list(numbers)
new_list = numbers[:]           # Slicing method
```

#### List Comprehension

```python
# Basic syntax: [expression for item in iterable]

squares = [x**2 for x in range(1, 6)]
print(squares)      # [1, 4, 9, 16, 25]

# With condition
evens = [x for x in range(10) if x % 2 == 0]
print(evens)        # [0, 2, 4, 6, 8]
```

---

### 4.2 Tuples

A **tuple** is an ordered, **immutable** (unchangeable), and indexed collection.

#### Creating Tuples

```python
# Empty tuple
empty = ()
empty = tuple()

# Tuple with values
coordinates = (10, 20)
person = ("Alice", 20, "Delhi")

# Single element tuple (note the comma!)
single = (5,)       # (5,) — comma is mandatory
not_tuple = (5)     # 5 — this is just an integer

# Tuple without parentheses
values = 1, 2, 3    # (1, 2, 3)
```

#### Accessing Tuple Elements

```python
t = ("a", "b", "c", "d", "e")

print(t[0])         # a
print(t[-1])        # e
print(t[1:4])       # ('b', 'c', 'd')
```

#### Tuple Operations

```python
t1 = (1, 2, 3)
t2 = (4, 5, 6)

# Concatenation
print(t1 + t2)      # (1, 2, 3, 4, 5, 6)

# Repetition
print(t1 * 2)       # (1, 2, 3, 1, 2, 3)

# Membership
print(2 in t1)      # True

# Length
print(len(t1))      # 3

# Unpacking
a, b, c = t1
print(a, b, c)      # 1 2 3
```

#### Why Use Tuples?

| Feature | List | Tuple |
|---------|------|-------|
| Mutable | Yes | No |
| Performance | Slower | Faster |
| Use Case | Dynamic data | Fixed data (coordinates, RGB values) |
| Dictionary Keys | No | Yes |

---

### 4.3 Sets

A **set** is an **unordered**, **unindexed** collection of **unique** elements.

#### Creating Sets

```python
# Empty set (note: {} creates a dictionary!)
empty = set()

# Set with values
fruits = {"apple", "banana", "cherry"}
numbers = {1, 2, 3, 4, 5}

# From list (removes duplicates)
unique = set([1, 2, 2, 3, 3, 3])    # {1, 2, 3}
```

#### Set Operations

```python
A = {1, 2, 3, 4, 5}
B = {4, 5, 6, 7, 8}

# Union: elements in A OR B
print(A | B)            # {1, 2, 3, 4, 5, 6, 7, 8}
print(A.union(B))

# Intersection: elements in A AND B
print(A & B)            # {4, 5}
print(A.intersection(B))

# Difference: elements in A but NOT in B
print(A - B)            # {1, 2, 3}
print(A.difference(B))

# Symmetric Difference: elements in A OR B but NOT both
print(A ^ B)            # {1, 2, 3, 6, 7, 8}
print(A.symmetric_difference(B))
```

#### Set Methods

```python
s = {1, 2, 3}

# Adding elements
s.add(4)                # {1, 2, 3, 4}
s.update([5, 6])        # {1, 2, 3, 4, 5, 6}

# Removing elements
s.remove(3)             # Removes 3, raises KeyError if not found
s.discard(10)           # Removes 10, no error if not found
popped = s.pop()        # Removes and returns arbitrary element
s.clear()               # Removes all elements
```

---

### 4.4 Strings

A **string** is a sequence of characters enclosed in quotes.

#### Creating Strings

```python
s1 = 'Hello'            # Single quotes
s2 = "World"            # Double quotes
s3 = '''Multi-line
string'''               # Triple quotes
```

#### String Indexing and Slicing

```python
text = "Python Programming"

print(text[0])          # P
print(text[-1])         # g
print(text[0:6])        # Python
print(text[7:])         # Programming
print(text[::2])        # Pto rgamn
print(text[::-1])       # gnimmargorP nohtyP (reversed)
```

#### String Methods

```python
text = "  Hello, Python World!  "

# Case conversion
print(text.upper())         # HELLO, PYTHON WORLD!
print(text.lower())         # hello, python world!
print(text.title())         # Hello, Python World!

# Stripping whitespace
print(text.strip())         # "Hello, Python World!"
print(text.lstrip())        # "Hello, Python World!  "
print(text.rstrip())        # "  Hello, Python World!"

# Finding and replacing
print(text.find("Python"))      # 9 (index of first occurrence)
print(text.count("o"))          # 3
print(text.replace("Python", "Java"))

# Splitting and joining
words = text.split()            # ['Hello,', 'Python', 'World!']
print("-".join(words))          # Hello,-Python-World!

# Checking properties
print("abc123".isalnum())       # True
print("abc".isalpha())          # True
print("123".isdigit())          # True
print("hello".startswith("he")) # True
print("world".endswith("ld"))   # True
```

#### String Formatting

```python
name = "Alice"
age = 20

# f-strings (recommended)
print(f"My name is {name} and I am {age} years old.")

# format() method
print("My name is {} and I am {} years old.".format(name, age))

# % formatting
print("My name is %s and I am %d years old." % (name, age))
```

---

### 4.5 Dictionaries

A **dictionary** is an unordered, mutable collection of **key-value pairs**.

#### Creating Dictionaries

```python
# Empty dictionary
empty = {}
empty = dict()

# Dictionary with values
student = {
    "name": "Alice",
    "age": 20,
    "grade": "A",
    "courses": ["Math", "Physics", "CS"]
}

# Using dict() constructor
person = dict(name="Bob", age=25, city="Delhi")
```

#### Accessing Dictionary Elements

```python
student = {"name": "Alice", "age": 20, "grade": "A"}

# Using key
print(student["name"])        # Alice

# Using get() (safer — returns None instead of error)
print(student.get("name"))    # Alice
print(student.get("marks"))   # None
print(student.get("marks", 0)) # 0 (default value)

# Accessing all keys, values, and items
print(student.keys())         # dict_keys(['name', 'age', 'grade'])
print(student.values())       # dict_values(['Alice', 20, 'A'])
print(student.items())        # dict_items([('name', 'Alice'), ...])
```

#### Modifying Dictionaries

```python
student = {"name": "Alice", "age": 20}

# Adding/Updating
student["grade"] = "A"        # Add new key
student["age"] = 21           # Update existing key
student.update({"city": "Delhi", "marks": 95})

# Removing
popped = student.pop("age")   # Removes and returns value
student.popitem()             # Removes and returns last inserted item
student.clear()               # Removes all items

del student["name"]           # Deletes key-value pair
```

#### Dictionary Methods

```python
d = {"a": 1, "b": 2, "c": 3}

# Copying
new_d = d.copy()

# Merging dictionaries
d1 = {"a": 1, "b": 2}
d2 = {"b": 3, "c": 4}
d1.update(d2)               # {'a': 1, 'b': 3, 'c': 4}

# Dictionary comprehension
squares = {x: x**2 for x in range(1, 6)}
print(squares)              # {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}

# Nested dictionaries
students = {
    "Alice": {"age": 20, "grade": "A"},
    "Bob": {"age": 22, "grade": "B"}
}
print(students["Alice"]["grade"])   # A
```

#### Built-in Functions for Data Structures

```python
# Common built-in functions
numbers = [3, 1, 4, 1, 5, 9, 2]

print(len(numbers))         # 7
print(max(numbers))         # 9
print(min(numbers))         # 1
print(sum(numbers))         # 25
print(sorted(numbers))      # [1, 1, 2, 3, 4, 5, 9]
print(list(enumerate(numbers)))  # [(0, 3), (1, 1), ...]
print(list(zip([1, 2], ['a', 'b'])))  # [(1, 'a'), (2, 'b')]

# Type conversion
print(list("abc"))          # ['a', 'b', 'c']
print(tuple([1, 2, 3]))     # (1, 2, 3)
print(set([1, 2, 2, 3]))    # {1, 2, 3}
print(dict([("a", 1)]))     # {'a': 1}
```

---

## 5. Unit-IV: File Handling and Introduction to Libraries

> **Weightage:** ~15 Marks | **Lectures:** 10-12

---

### 5.1 File Handling

File handling allows programs to create, read, write, and manipulate files stored on disk.

#### Opening a File

The `open()` function opens a file and returns a file object.

```python
# Syntax: open(filename, mode)

file = open("data.txt", "r")    # Open for reading
file = open("data.txt", "w")    # Open for writing
file = open("data.txt", "a")    # Open for appending
file = open("data.txt", "r+")   # Open for reading and writing
```

#### File Modes

| Mode | Description | Behavior |
|------|-------------|----------|
| `r` | Read | Opens for reading (default). File must exist. |
| `w` | Write | Opens for writing. Creates new file or truncates existing. |
| `a` | Append | Opens for appending. Creates new file if doesn't exist. |
| `x` | Exclusive Creation | Creates new file. Fails if file exists. |
| `r+` | Read + Write | Opens for both reading and writing. |
| `w+` | Write + Read | Opens for both. Truncates existing file. |
| `a+` | Append + Read | Opens for both. Pointer at end. |
| `b` | Binary | Used with above modes for binary files (`rb`, `wb`). |
| `t` | Text | Used with above modes for text files (`rt`, `wt`). |

#### Reading from Files

```python
# Method 1: read() — reads entire file
with open("data.txt", "r") as file:
    content = file.read()
    print(content)

# Method 2: readline() — reads one line at a time
with open("data.txt", "r") as file:
    line = file.readline()
    while line:
        print(line.strip())
        line = file.readline()

# Method 3: readlines() — reads all lines into a list
with open("data.txt", "r") as file:
    lines = file.readlines()
    for line in lines:
        print(line.strip())

# Method 4: Iterate over file object (most Pythonic)
with open("data.txt", "r") as file:
    for line in file:
        print(line.strip())
```

#### Writing to Files

```python
# Writing (overwrites existing content)
with open("output.txt", "w") as file:
    file.write("Hello, World!\n")
    file.write("This is line 2.\n")

# Appending (adds to existing content)
with open("output.txt", "a") as file:
    file.write("This is appended.\n")

# Writing multiple lines
lines = ["Line 1\n", "Line 2\n", "Line 3\n"]
with open("output.txt", "w") as file:
    file.writelines(lines)
```

#### Using `with` Statement (Context Manager)

The `with` statement ensures the file is properly closed after operations, even if an error occurs.

```python
# Without with (not recommended)
file = open("data.txt", "r")
content = file.read()
file.close()        # Must close manually

# With with (recommended)
with open("data.txt", "r") as file:
    content = file.read()
# File is automatically closed here
```

#### File Position and Seeking

```python
with open("data.txt", "r") as file:
    print(file.tell())      # Current position (0)
    file.read(5)            # Read 5 characters
    print(file.tell())      # Current position (5)
    file.seek(0)            # Move to beginning
    print(file.read())      # Read from beginning
```

#### Checking if File Exists

```python
import os

if os.path.exists("data.txt"):
    with open("data.txt", "r") as file:
        print(file.read())
else:
    print("File does not exist.")

# Other useful os functions
print(os.path.getsize("data.txt"))      # File size in bytes
print(os.path.isfile("data.txt"))       # True if it's a file
print(os.path.isdir("folder"))          # True if it's a directory
```

#### Practical Example: Student Record System

```python
# Writing student data
def add_student(name, marks):
    with open("students.txt", "a") as file:
        file.write(f"{name},{marks}\n")

# Reading student data
def display_students():
    with open("students.txt", "r") as file:
        print("Name\t\tMarks")
        print("-" * 25)
        for line in file:
            name, marks = line.strip().split(",")
            print(f"{name}\t\t{marks}")

# Main program
add_student("Alice", 85)
add_student("Bob", 92)
add_student("Charlie", 78)
display_students()
```

---

### 5.2 Introduction to Python Libraries

Python's power comes from its vast ecosystem of libraries. A **library** is a collection of pre-written code that you can use in your programs.

#### Installing Libraries

```bash
# Using pip (Python's package manager)
pip install numpy
pip install pandas

# Using conda (if using Anaconda)
conda install numpy
conda install pandas
```

#### Importing Libraries

```python
# Import entire module
import math
print(math.sqrt(16))        # 4.0

# Import with alias
import numpy as np
import pandas as pd

# Import specific functions
from math import sqrt, pi
print(sqrt(25))             # 5.0
print(pi)                   # 3.14159...
```

---

### 5.3 Introduction to NumPy

**NumPy** (Numerical Python) is the fundamental package for scientific computing in Python.

#### Why NumPy?

| Feature | Python List | NumPy Array |
|---------|-------------|-------------|
| Speed | Slower | Faster (C-optimized) |
| Memory | More | Less |
| Operations | Element-wise loops | Vectorized operations |
| Data Type | Mixed | Homogeneous |

#### Creating NumPy Arrays

```python
import numpy as np

# From list
arr1 = np.array([1, 2, 3, 4, 5])

# 2D array (matrix)
arr2 = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])

# Special arrays
zeros = np.zeros((3, 3))          # 3x3 array of zeros
ones = np.ones((2, 4))            # 2x4 array of ones
identity = np.eye(3)              # 3x3 identity matrix
arange = np.arange(0, 10, 2)      # [0, 2, 4, 6, 8]
linspace = np.linspace(0, 1, 5)   # [0, 0.25, 0.5, 0.75, 1]

# Random arrays
random_arr = np.random.rand(3, 3)     # 3x3 random values (0-1)
random_int = np.random.randint(1, 10, (2, 3))  # 2x3 random integers
```

#### Array Properties

```python
arr = np.array([[1, 2, 3], [4, 5, 6]])

print(arr.shape)        # (2, 3) — dimensions
print(arr.ndim)         # 2 — number of dimensions
print(arr.size)         # 6 — total elements
print(arr.dtype)        # int64 — data type
print(arr.itemsize)     # 8 — bytes per element
```

#### Array Operations

```python
a = np.array([1, 2, 3])
b = np.array([4, 5, 6])

# Arithmetic operations (vectorized)
print(a + b)            # [5, 7, 9]
print(a - b)            # [-3, -3, -3]
print(a * b)            # [4, 10, 18]
print(a / b)            # [0.25, 0.4, 0.5]
print(a ** 2)           # [1, 4, 9]

# Statistical operations
print(np.sum(a))        # 6
print(np.mean(a))       # 2.0
print(np.max(a))        # 3
print(np.min(a))        # 1
print(np.std(a))        # 0.816...

# Matrix operations
A = np.array([[1, 2], [3, 4]])
B = np.array([[5, 6], [7, 8]])

print(np.dot(A, B))     # Matrix multiplication
print(A.T)              # Transpose
print(np.linalg.inv(A)) # Inverse
print(np.linalg.det(A)) # Determinant
```

#### Array Indexing and Slicing

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])

print(arr[0, 1])        # 2 (row 0, column 1)
print(arr[1, :])        # [4, 5, 6] (entire row 1)
print(arr[:, 1])        # [2, 5, 8] (entire column 1)
print(arr[0:2, 1:3])    # [[2, 3], [5, 6]]

# Boolean indexing
print(arr[arr > 5])     # [6, 7, 8, 9]
```

---

### 5.4 Introduction to Pandas

**Pandas** is a powerful library for data manipulation and analysis.

#### Core Data Structures

| Structure | Description | Analogy |
|-----------|-------------|---------|
| **Series** | 1D labeled array | Column in a spreadsheet |
| **DataFrame** | 2D labeled data structure | Entire spreadsheet |

#### Creating Series

```python
import pandas as pd

# From list
s = pd.Series([10, 20, 30, 40])
print(s)

# With custom index
s = pd.Series([10, 20, 30], index=["a", "b", "c"])
print(s["b"])           # 20

# From dictionary
s = pd.Series({"Alice": 85, "Bob": 92, "Charlie": 78})
```

#### Creating DataFrames

```python
# From dictionary
data = {
    "Name": ["Alice", "Bob", "Charlie"],
    "Age": [20, 22, 19],
    "Marks": [85, 92, 78]
}
df = pd.DataFrame(data)
print(df)
```

#### Basic DataFrame Operations

```python
# Display first/last rows
print(df.head())        # First 5 rows
print(df.tail(2))       # Last 2 rows

# Information
print(df.shape)         # (rows, columns)
print(df.columns)       # Column names
print(df.dtypes)        # Data types
print(df.info())        # Summary info
print(df.describe())    # Statistical summary

# Selecting columns
print(df["Name"])       # Single column (Series)
print(df[["Name", "Age"]])  # Multiple columns (DataFrame)

# Selecting rows
print(df.iloc[0])       # First row (by position)
print(df.loc[0])        # First row (by label)
print(df.iloc[0:2])     # First two rows

# Filtering
print(df[df["Marks"] > 80])     # Students with marks > 80
print(df[df["Age"] >= 20])      # Students with age >= 20
```

#### Reading and Writing Data

```python
# Reading CSV
df = pd.read_csv("data.csv")

# Reading Excel
df = pd.read_excel("data.xlsx")

# Writing to CSV
df.to_csv("output.csv", index=False)

# Writing to Excel
df.to_excel("output.xlsx", index=False)
```

#### Data Manipulation

```python
# Adding a new column
df["Grade"] = ["A", "A+", "B"]

# Removing a column
df = df.drop("Grade", axis=1)

# Sorting
df_sorted = df.sort_values("Marks", ascending=False)

# Grouping
grouped = df.groupby("Age").mean()

# Handling missing values
df.isnull().sum()       # Count missing values per column
df.dropna()             # Remove rows with missing values
df.fillna(0)            # Fill missing values with 0
```

---

## 6. Course Outcomes (COs)

Upon successful completion of this course, students will be able to:

| CO | Outcome | Description |
|----|---------|-------------|
| **CO1** | Understand Python Syntax | Understand Python syntax, data types, and basic programming concepts. |
| **CO2** | Apply Control Structures | Apply control structures and functions to solve computational problems. |
| **CO3** | Utilize Data Structures | Utilize Python data structures for efficient data manipulation. |
| **CO4** | Develop Applications | Develop simple applications using file handling and modular programming concepts. |

### CO-Unit Mapping

| Course Outcome | Unit-I | Unit-II | Unit-III | Unit-IV |
|----------------|--------|---------|----------|---------|
| **CO1** | ✅ | ✅ | | |
| **CO2** | | ✅ | | |
| **CO3** | | | ✅ | |
| **CO4** | | | | ✅ |

---

## 7. Examination Pattern

### Theory Examination (60 Marks)

The External End Semester Theory Examination will be divided into two sections:

#### Section A — Short Answer Questions (Compulsory)

| Detail | Value |
|--------|-------|
| Number of Questions | 4 (one from each unit) |
| Marks per Question | 3 |
| Total Marks | 12 |
| Nature | **Compulsory** — all must be attempted |

#### Section B — Long Answer Questions

| Detail | Value |
|--------|-------|
| Number of Questions | 8 (two from each unit) |
| Marks per Question | 12 |
| Questions to Attempt | 4 (one from each unit) |
| Total Marks | 48 |

#### Total Theory Marks

```
Section A: 4 questions x 3 marks  = 12 marks
Section B: 4 questions x 12 marks = 48 marks
                                    --------
Total Theory Marks                = 60 marks
```

### Internal Assessment (25 Marks)

| Component | Marks |
|-----------|-------|
| Class Tests / Quizzes | 10 |
| Assignments | 10 |
| Attendance & Participation | 5 |
| **Total** | **25** |

### Practical Examination (15 Marks)

| Component | Marks |
|-----------|-------|
| Lab Performance | 8 |
| Practical File / Record | 4 |
| Viva-Voce | 3 |
| **Total** | **15** |

---

## 8. Practice Questions

### Unit-I: Introduction to Python

1. Explain the features and applications of Python programming language.
2. Differentiate between compiled and interpreted languages. Why is Python called an interpreted language?
3. Write a Python program to demonstrate the use of all arithmetic operators.
4. What are keywords and identifiers? List the rules for naming identifiers in Python.
5. Explain the different data types in Python with examples.
6. Write a program to swap two numbers using a temporary variable and without using a temporary variable.
7. Explain the `input()` and `print()` functions with examples.
8. What are the different types of operators in Python? Explain with examples.

### Unit-II: Control Structures and Functions

1. Explain the `if`, `if-else`, and `if-elif-else` statements with examples.
2. Differentiate between `for` loop and `while` loop with suitable examples.
3. Write a program to print the Fibonacci series up to n terms using both `for` and `while` loops.
4. Explain the use of `break`, `continue`, and `pass` statements with examples.
5. What are nested loops? Write a program to print a pyramid pattern using nested loops.
6. Define a function. Explain the different types of arguments in Python functions.
7. Write a recursive function to calculate the factorial of a number.
8. Explain lambda functions with examples. How are they different from regular functions?

### Unit-III: Data Structures

1. What is a list? Explain list operations and methods with examples.
2. Differentiate between lists and tuples. When should you use a tuple over a list?
3. Write a program to find the largest and smallest elements in a list without using built-in functions.
4. Explain set operations (union, intersection, difference) with examples.
5. What are strings? Explain string slicing and common string methods.
6. Write a program to check if a string is a palindrome.
7. Explain dictionaries in Python. How do you add, remove, and update elements?
8. Write a program to count the frequency of each character in a string using a dictionary.

### Unit-IV: File Handling and Libraries

1. Explain file handling in Python. What are the different file modes?
2. Write a program to read a text file and count the number of words, lines, and characters.
3. Explain the `with` statement in file handling. Why is it preferred?
4. Write a program to copy the contents of one file to another.
5. What is NumPy? Explain how to create and manipulate NumPy arrays.
6. Differentiate between Python lists and NumPy arrays.
7. What is Pandas? Explain Series and DataFrame with examples.
8. Write a program to read a CSV file using Pandas and display basic statistics.

---

## 9. Suggested Readings

### Textbooks

| # | Author & Title | Publisher | Year |
|---|----------------|-----------|------|
| 1 | **Reema Thareja**, *Python Programming Using Problem Solving Approach* | Oxford University Press | 2017 |
| 2 | **Allen B. Downey**, *Think Python: How to Think Like a Computer Scientist* | O'Reilly Media | 2016 |
| 3 | **Eric Matthes**, *Python Crash Course* | No Starch Press | 2019 |

### Online Resources

| Resource | Link | Description |
|----------|------|-------------|
| Official Python Documentation | [docs.python.org/3](https://docs.python.org/3/) | Comprehensive official documentation |
| W3Schools Python | [w3schools.com/python](https://www.w3schools.com/python/) | Interactive tutorials |
| GeeksforGeeks Python | [geeksforgeeks.org/python-programming-language](https://www.geeksforgeeks.org/python-programming-language/) | Articles and practice problems |
| Real Python | [realpython.com](https://realpython.com/) | In-depth tutorials |
| NumPy Documentation | [numpy.org/doc](https://numpy.org/doc/) | Official NumPy docs |
| Pandas Documentation | [pandas.pydata.org/docs](https://pandas.pydata.org/docs/) | Official Pandas docs |

---

<div align="center">

## 🎓 Best of Luck for Your Examination!

> *"The best way to learn programming is to write code. Start small, think big, and never stop coding."*

[![Python](https://img.shields.io/badge/Keep%20Coding-Python-3776AB?style=for-the-badge&logo=python)](https://www.python.org/)

</div>

---

*Course Material for B.Tech/B.Sc Data Science & AI | Semester 3 | Batch 2026-30*

*Last Updated: August 2026*