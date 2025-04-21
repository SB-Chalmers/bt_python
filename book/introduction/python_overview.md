# Python Overview

This section provides a quick introduction to Python's structure, syntax, and basic concepts. It's designed for complete beginners!

---

## Python Program Structure

Python code is written in plain text files with a `.py` extension. Each line is a statement, and indentation (spaces or tabs) is used to define blocks of code.

Example:
```python
# This is a comment
print("Hello, world!")  # This prints text to the screen
```

---

## Variables

Variables store data. You don't need to declare their type.

```python
name = "Alice"
age = 25
height = 1.68
```

---

## Data Types

- **int**: Integer numbers (`42`)
- **float**: Decimal numbers (`3.14`)
- **str**: Text (`"hello"`)
- **bool**: Boolean (`True` or `False`)
- **list**: Ordered collection (`[1, 2, 3]`)
- **dict**: Key-value pairs (`{"name": "Alice", "age": 25}`)

---

## Operators

- **Arithmetic:** `+`, `-`, `*`, `/`, `//` (integer division), `%` (modulo), `**` (power)
- **Comparison:** `==`, `!=`, `<`, `>`, `<=`, `>=`
- **Logical:** `and`, `or`, `not`

Example:
```python
a = 10
b = 3
print(a + b)      # 13
print(a / b)      # 3.333...
print(a > b)      # True
print(a == 10 and b < 5)  # True
```

---

## Conditionals

Use `if`, `elif`, and `else` to make decisions.

```python
age = 18
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

---

## Loops

- **for** loops: Iterate over a sequence.
- **while** loops: Repeat while a condition is true.

```python
# For loop
for i in range(5):
    print(i)

# While loop
count = 0
while count < 3:
    print(count)
    count += 1
```

---

## Functions

Functions group code into reusable blocks.

```python
def greet(name):
    print("Hello,", name)

greet("Alice")
```

---

## Classes

Classes are blueprints for creating objects (instances) and are used in object-oriented programming.

```python
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def say_hello(self):
        print(f"Hello, my name is {self.name}.")

alice = Person("Alice", 25)
alice.say_hello()
```

---

## Libraries and Modules

Python has a rich ecosystem of libraries (also called modules) that extend its functionality. You can import and use them in your code.

```python
import math

print(math.sqrt(16))  # Outputs: 4.0
```

You can also create your own modules by saving functions and classes in `.py` files and importing them.

---

## Installing Packages with pip

`pip` is Python's package manager. Use it to install external libraries from the Python Package Index (PyPI).

```sh
pip install requests
```

Then, you can use the installed package in your code:

```python
import requests

response = requests.get("https://www.example.com")
print(response.status_code)
```

---

## Comments

Use `#` for single-line comments.

---

## Summary

- Python uses indentation to define code blocks.
- Variables are created by assignment.
- Common types: int, float, str, bool, list, dict.
- Use operators for math and logic.
- Use `if` statements for decisions, loops for repetition.
- Functions help organize code.
- Classes let you create your own data types.
- Libraries and pip let you use and install extra functionality.

You're now ready to start experimenting with Python code!
