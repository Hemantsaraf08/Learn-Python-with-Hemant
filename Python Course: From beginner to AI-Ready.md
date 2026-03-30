<p><a target="_blank" href="https://app.eraser.io/workspace/bdwutKp3ZwO4kvK7lYhr" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

Python is one of the world’s most popular programming languages today. It is used in exciting fields like AI, Data Science, Data Analytics, and even in building web applications—showing how powerful and versatile it is.

Most beginners start their coding journey with Python because it is simple, easy to read, and quick to learn. Whether you want to score better in exams or build real-world projects, Python is the perfect first step into the world of technology.

**Why Join This Course?**

- 🌟 **Absolute Beginner Friendly:** We start from zero. If you can read English, you can code in Python.
- 💻 **100% Hands-On:** No boring theory. You will write code in every single class.
- 🔴 **Live Classes & Live Coding:** Watch your instructor build apps in real-time and get your doubts cleared instantly.
- 🏏 **Real-World Projects:** Build projects like Cricket Scoreboards, Currency Converters (INR to USD) and many more based on your interests!
## Course Outline
### Part 1: The Building Blocks (Logic & Syntax)
- [ ] **Setup and intro to python: **Install VS Code and the Python interpreter. Write your first print("Hello World") and understand how Python translates your code for the machine.
- [ ] **Variables & Types:** Learn how Python stores data in "memory locations". We'll cover Strings (text), Integers/Floats (numbers), and Booleans (True/False).
- [ ] **Conditional Logic:** Make your programs "think" using if, elif, and else.
- [ ] **Iterative Logic (Part 1): **Master the for loop and the range() function to repeat tasks effortlessly.
- [ ] **Iterative Logic (Part 2):** Use while loops for indefinite tasks and learn to control them with break and continue.
- [ ] **Weekend Mini Project:** Build a simple "Cricket Scoreboard" or an "INR to USD Currency Converter" using input functions and basic arithmetic operators.
### Part 2: Data Structures & Modularity 
- [ ] **Lists: **Dive into Python’s most versatile "storage box." Learn indexing, slicing (accessing parts of a list), and common methods like append() and sort().
- [ ] **Dictionaries & Tuples: **Store "Key-Value" pairs (like a student’s roll number and name) and learn about Immutability with Tuples.
- [ ] **Functions (Part 1):** Learn to write reusable "blocks of code" using def, parameters, and return.
- [ ] **Functions (Part 2):** Understand Local vs. Global scope—where your variables "live" and die.
- [ ] **Iterative Logic (Part 2):** Use while loops for indefinite tasks and learn to control them with break and continue.
- [ ] **Introduction to Modules:** Use Python’s built-in libraries like math for complex calculations and random to build a "Dice Simulator" for board games.
- [ ] **Weekend Practise: **Practise of Functions and modules in python with real world application examples.
### Part 3: Real-World Data (The Bridge to AI) 
- [ ] **Exception Handling:** Make your code "crash-proof" using try and except to handle user errors gracefully.
- [ ] **File Handling: **Learn how Python reads from and writes to .txt files so your data is saved even after you turn off the computer.
- [ ] **CSV & Persistence: **Manage data in Excel-like formats using the csv module.
- [ ] **Introduction to NumPy:** Transition from Lists to Arrays. Think of NumPy as "Excel on Steroids" for Python.
- [ ] **Weekend Mini Project:** 
    - [ ]  Build a "Student Record System" that permanently saves names and marks to a file. 
    - [ ] Analyze IPL cricket data using basic NumPy arrays.

### Part 4: Object-Oriented Programming and Debugging 
- [ ] **OOP Basics:** Introduction to Object-Oriented Programming. Learn how to use "Classes" as blueprints to create "Objects".
- [ ] **OOP Continued...**
- [ ] **Debugging:** Learn how to read Tracebacks (error messages) and debug your code.
### Part 5: Capstone Projects 🎓 
- [ ] **Capstone Phase:** Finalize your choice.
- [ ] **Build project in hackathon mode!**
- [ ] **Final Demo & Future Path: **Present your project, participate in an **AMA (Ask Me Anything) call** and receive guidance on any topic.
---

## Part 1: The building blocks
### Python Interpreter: Translates human readable code to machine code


![python_interpreter.png](/.eraser/bdwutKp3ZwO4kvK7lYhr___mlrANIZvmbfebVXPeDhQXqWoD3x1___python_interpreter_pAAWWGGYOqfGhvtwMxw9s.png "python_interpreter.png")



- [ ] Download and Install VS code
- [ ] Download python interpreter for windows/mac
- [ ] Your first python program: make a hello.py file
- [ ] run the file using python interpreter
### Data-type and the_ type_ function: 
#### Basic data-types in python are: _Strings, Numbers (integer and floating) and Boolean (True or False)_
To know the type of any value, you can use the _type _function which python provides:

```
>>> type('Hello, World!')
<class 'str'>
>>> type(17)
<class 'int'>
>>> type(3.2)
<class 'float'>
>>> type('17')
<class 'str'>
>>> type('3.2')
<class 'str'>
```
### Variables
A variable is a name that refers to a value. Just like we do x=1 in maths, we can do the same in our programs. 

Look at how we assign the variables to its values below: 

```
>>> message = 'And now for something completely different'
>>> age = 17
>>> pi = 3.142
```
Once the variable is assigned a value we can _"operate"_ on it, i.e. do whatever operations we want to do on that variable, like print it or check its type as shown below:

```
>>> print(n)
17
>>> print(pi)
3.142
>>> type(message)
<class 'str'>
>>> type(age)
<class 'int'>
>>> type(pi)
<class 'float'>
```
Think of variable name as the address in computers memory:

![variable_allocation_in_memory.png](/.eraser/bdwutKp3ZwO4kvK7lYhr___mlrANIZvmbfebVXPeDhQXqWoD3x1___variable_allocation_in_memory_HMzDttfRnMyMuPEKcZhUO.png "variable_allocation_in_memory.png")



### Variable names and keywords
Python has some rules and standards for variable naming as seen below: 

![variable_naming_rules.png](/.eraser/bdwutKp3ZwO4kvK7lYhr___mlrANIZvmbfebVXPeDhQXqWoD3x1___variable_naming_rules_CsfXpJRgCwr-rF8lNnoDi.png "variable_naming_rules.png")



If you give a variable an illegal name, you get a syntax error:

```
>>> 2states = 'movie'
SyntaxError: invalid syntax
>>> myage@ = 18
SyntaxError: invalid syntax
>>> class = 'Python Course'
SyntaxError: invalid syntax
```
`2states` is illegal because it begins with a number. `﻿myage@` is illegal because it contains an illegal character, @. But what’s wrong with `class`?

It turns out that `class` is one of Python’s _keywords_. The interpreter uses keywords to recognize the structure of the program, and they cannot be used as variable names.

Python reserves 35 keywords:

```
False      await      else       import     pass
None       break      except     in         raise
True       class      finally    is         return
and        continue   for        lambda     try
as         def        from       nonlocal   while
assert     del        global     not        with
async      elif       if         or         yield
```
You don't have to memorize this, as it will come by practise, and anytime you use a keyword as a variable name, your IDE i.e. VS Code will complain and highlight the error while you type.

### Exercise:
- [ ] Taking user input
- [ ] 




<!--- Eraser file: https://app.eraser.io/workspace/bdwutKp3ZwO4kvK7lYhr --->