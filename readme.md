--------------# Inner Workings of Python---------------

-------------------**Written by: Faria Mustaqim**------------------

## Introduction to Python
Python was created by **Guido van Rossum**. It is an **interpreted language**, meaning the code is executed **line by line**.
- The main file in a Python project is often named **`main.py`**, which acts as the entry point.

---

## Python Environment & Tools
### IDE (Integrated Development Environment)
Software used to write and test Python code:
- **PyCharm**
- **VS Code**

### Cursor
The blinking line that shows where you are typing in the editor.

### Checking Python Version
Use the following command to check the installed Python version:
```sh
python --version  # or
py --version
```

---

## Communication with Hardware
- Computers understand only **binary (0s and 1s).**
- **Assembly language** is a low-level programming language that helps communicate with hardware.

---

## Programming Concepts in Python
- **Curly braces `{}`** are replaced with **colons `:`** in Python to define blocks of code.
- **Git** is used to track code changes and manage project versions.
- **Underscore `_`** in Python often signifies internal use.

---

## Types of Programming Languages
### Implicit Programming (Automatic Type Casting)
Python automatically converts one data type to another (e.g., `int` to `float`).

### Explicit Programming (Manual Type Declaration)
Manual type definition or conversion is needed (e.g., `int("5")`).

Python is an **implicit type language**, meaning type conversion happens automatically.

---

## Python Compilation Process
- Python code is first converted into **bytecode** before execution.
- Compiled Python files are stored as **`.pyc`** in the `__pycache__` folder.
- Python's most popular variant is **CPython**.

### Why Does Python Generate `.pyc` Files?
`.pyc` files are generated when importing a module to make execution **faster**.

---

## Execution Process in Python
1. Python code is **compiled into bytecode** (not machine code).
2. Bytecode is stored in a **cache**, making execution faster.
3. The **Python Virtual Machine (PVM)** executes the bytecode.
4. PVM runs in a loop and converts bytecode into **binary code** that the computer understands.
5. The **Python interpreter** is also known as a **runtime engine**, as it continuously runs and processes code.

---

## Different Processing Units
- **CPU (Central Processing Unit):** Executes general instructions.
- **GPU (Graphics Processing Unit):** Handles graphical tasks and parallel processing.
- **TPU (Tensor Processing Unit):** Specialized for machine learning tasks.

---

## Python Data Types
| Data Type        | Description                                   | Example              |
|-----------------|---------------------------------|--------------------|
| **String (str)** | Text values | `"hello"` |
| **Tuple (tuple)** | Collection of data, immutable | `(1, 2, 3)` |
| **Integer (int)** | Whole numbers | `5`, `100` |
| **Boolean (bool)** | True or False | `True`, `False` |
| **Dictionary (dict)** | Key-value pairs (like JSON objects) | `{"key": "value"}` |
| **Float (float)** | Decimal numbers | `3.14`, `2.5` |
| **List (list)** | Ordered collection (can be changed) | `[1, 2, 3]` |
| **Set (set)** | Unique values (removes duplicates) | `{1, 2, 3}` |
| **Frozen Set (frozenset)** | Similar to set, but unchangeable | `frozenset({1, 2, 3})` |
| **None (NoneType)** | Represents the absence of a value | `None` |

---

## Mutable vs Immutable Objects
- **Mutable (can be changed):** Lists, dictionaries, sets.
- **Immutable (cannot be changed):** Strings, tuples, frozensets.

---

## Python Naming Conventions
- Python uses **snake_case** for variable and function names (e.g., `example_variable`).
- **Indentation** is crucial (use **tabs** or **four spaces** to avoid errors).

---

## PEP 8
PEP 8 is the **official Python style guide** that provides best practices for writing **clean** and **readable** code.

---

## Author
📌 **Written by:** *Faria Mustaqim*
