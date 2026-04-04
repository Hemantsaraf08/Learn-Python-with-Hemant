<p><a target="_blank" href="https://app.eraser.io/workspace/nCNUkO1k04QolEB0AS51" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

Python is one of the world’s most popular programming languages today. It is used in exciting fields like AI, Data Science, Data Analytics, and even in building web applications—showing how powerful and versatile it is.

Most beginners start their coding journey with Python because it is simple, easy to read, and quick to learn. Whether you want to score better in exams or build real-world projects, Python is the perfect first step into the world of technology.

**Why Join This Course?**

- 🌟 **Absolute Beginner Friendly:** We start from zero. If you can read English, you can code in Python.
- 💻 **100% Hands-On:** No boring theory. You will write code in every single class.
- 🔴 **Live Classes & Live Coding:** Watch your instructor build apps in real-time and get your doubts cleared instantly.
- 🏏 **Real-World Projects:** Build projects like Cricket Scoreboards, Currency Converters (INR to USD) and many more based on your interests!
## Course Outline
### Part 1: The Building Blocks (Logic & Syntax)
- [ ] **Setup and intro to python:** Install VS Code and the Python interpreter. Write your first print("Hello World") and understand how Python translates your code for the machine.
- [ ] **Variables & Types:** Learn how Python stores data in "memory locations". We'll cover Strings (text), Integers/Floats (numbers), and Booleans (True/False).
- [ ] **Conditional Logic:** Make your programs "think" using if, elif, and else.
- [ ] **Iterative Logic (Part 1)**: Master the for loop and the range() function to repeat tasks effortlessly.
- [ ] **Iterative Logic (Part 2):** Use while loops for indefinite tasks and learn to control them with break and continue.
- [ ] **Weekend Mini Project:** Build a simple "Cricket Scoreboard" or an "INR to USD Currency Converter" using input functions and basic arithmetic operators.
### Part 2: Data Structures & Modularity
- [ ] **Lists:** Dive into Python’s most versatile "storage box." Learn indexing, slicing (accessing parts of a list), and common methods like append() and sort().
- [ ] **Dictionaries & Tuples:** Store "Key-Value" pairs (like a student’s roll number and name) and learn about Immutability with Tuples.
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
    - [ ] Build a "Student Record System" that permanently saves names and marks to a file. 
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
![python_interpreter.png](/.eraser/nCNUkO1k04QolEB0AS51___mlrANIZvmbfebVXPeDhQXqWoD3x1___python_interpreter_pAAWWGGYOqfGhvtwMxw9s.png "python_interpreter.png")

- [ ] Create new notebook on google collab
- [ ] Your first python program: make a hello.py file
- [ ] run the file using python interpreter
### Data-type and the type function:
#### Basic data-types in python are: _Strings, Numbers (integer and floating) and Boolean (True or False) and None_
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

![variable_allocation_in_memory.png](/.eraser/nCNUkO1k04QolEB0AS51___mlrANIZvmbfebVXPeDhQXqWoD3x1___variable_allocation_in_memory_HMzDttfRnMyMuPEKcZhUO.png "variable_allocation_in_memory.png")

### Variable names and keywords
Python has some rules and standards for variable naming as seen below: 

![variable_naming_rules.png](/.eraser/nCNUkO1k04QolEB0AS51___mlrANIZvmbfebVXPeDhQXqWoD3x1___variable_naming_rules_CsfXpJRgCwr-rF8lNnoDi.png "variable_naming_rules.png")

If you give a variable an illegal name, you get a syntax error:

```
>>> 2states = 'movie'
SyntaxError: invalid syntax
>>> myage@ = 18
SyntaxError: invalid syntax
>>> class = 'Python Course'
SyntaxError: invalid syntax
```
`2states` is illegal because it begins with a number. ` myage@` is illegal because it contains an illegal character, @. But what’s wrong with `class`?

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
- [ ] Asking user his name and greeting him
- [ ] Use type function to check types of number, string, boolean
### Commenting Your Code
As programs get bigger and more complicated, they get more difficult to read. It is often difficult to look at a piece of code and figure out what it is doing, or why.

For this reason, it is a good idea to add notes to your programs to explain to the readers of the code what the program is doing. These notes are called _comments_, and in Python they start with the `#` symbol:

```
# compute the percentage of the hour that has elapsed
percentage = (minute * 100) / 60
```
If we want to give a multiline description of the code, we use **Docstrings** (Triple-quoted strings) for multiline commenting:  

```
"""
This is a form of a multi-line comment.
this form of commenting is not used for general purpose.
Its called Docstring for a specific reason, which we will discover later
"""
```
### Python Operators
![Screenshot 2026-03-31 at 10.49.44 PM.png](/.eraser/nCNUkO1k04QolEB0AS51___mlrANIZvmbfebVXPeDhQXqWoD3x1___Screenshot%202026-03-31%20at%2010.49 "Screenshot 2026-03-31 at 10.49.44 PM.png")



Apart from the above operators, its useful to know the below operators: 

1. Exponential operator: **
2. String Operators: We can use arithmetic operators like + (for concatenation), * (for multiplying the content of a string by an integer)  
### Exercise: 
- [ ] WAP to input a word and a number (num), then print the word num times
- [ ] WAP to ask user his first_name and last_name and print his full name
- [ ] Write a program to input 2 numbers and print the sum (Intro to explicit type conversion)
- [ ] WAP to input side of a square and print its area 
- [ ] What will this program print: `﻿print("5" + "5")` 
- [ ] what wil this program print: `print(int("5") + int("5"))` 
- [ ] WAP to get avg of 2 floating point numbers
- [ ] WAP to input 2 numbers a and b and print True if a is greater than or equal to b
### Type Conversion: 
- **Implicit type conversion**
- **Explicit type conversion**
### Explicit Type Conversion:
Explicit conversion, also called type casting, is when a programmer manually changes a value from one data type to another.

- Done using Python's build-in function like **int()**, **float()**, **str() and bool()**. Number 0 will be False and other numbers are True. Empty strings (no ASCII value) are False, others are True 
- Gives full control over how data is interpreted or processed.
#### Common type casting functions
- **int() **converts a value to an integer
- **float()** converts a value to a floating point number
- **str()** converts a value to a string
- **bool() **converts a value to a Boolean (True/False)
### Implicit type conversion:
Implicit conversion in Python happens automatically when different data types are used together in an expression.

- Python converts a smaller data type to a larger one when needed.
- Commonly occurs when integers and floats are combined.
- Conversion happens at runtime to keep results accurate.
```
x = 10          # Integer
y = 10.6        # Float
z = x + y     

print("x:", type(x))
print("y:", type(y))
print("z =", z)
print("z :", type(z))
```
Output: 

```
x: <class 'int'>
y: <class 'float'>
z = 20.6
z : <class 'float'>
```
### Exercise (Variables and operators):
- [ ] Write a program to input the **Principal (P)**, **Rate (R)**, and **Time (T)** from the user. Calculate the Simple Interest using the formula `SI = (P * R * T) / 100` .
- [ ] Input a number and print True if the number is Even, else print False
- [ ] Predict output: 
`a, b = 10, 2.0
``c = a * b
`what is the type of variable "c" and its value


**Conditional Logic (Making Decisions) **

**What are Conditionals?**

In real life, we make decisions every day:

- **If** it is raining, **then** I will take an umbrella.
- **Else**, I will wear my favorite sunglasses.
In programming, **Conditional Statements **allow your code to "think" and perform different actions

based on whether a condition is `True` or `False` 

**The "Questions" (Comparison Operators)**

Before a program can decide, it must compare values. Python uses these symbols to ask questions:

- == : Is equal to? (Don't confuse with `=` , which assigns a value).
- !=  : Not equal to?.
- `>`  / `<`  : Greater than / Less than?.
- >=  / <=  : Greater than or equal to / Less than or equal to?.
Logical Operators (The "And/Or" Logic):

- `and` : True if **both** conditions are met (e.g., You have a ticket **and** you are on time).
- `or` : True if **at least one** condition is met (e.g., It is Sunday **or** it is a public holiday).
- `﻿not` : True if the condition DOESN'T MEET, (e.g: age is not <18, then eligible to vote)


**The  if Statement (The Basic Check)**

The `if`  statement is the simplest form of control. If the condition is true, the indented code runs. If it's false, Python simply skips it.

![python-if-statement.png](/.eraser/nCNUkO1k04QolEB0AS51___mlrANIZvmbfebVXPeDhQXqWoD3x1___python-if-statement_fTfaP8oH8S7madNkMgNji.png "python-if-statement.png")



**Syntax:**

```
if condition:
# This code runs only if condition is True, note that 
```
**Example:**

```
age = int(input("Enter your age: "))
if age >= 18:
    print("You are eligible for a driving license in India!")
```
**The if-else Statement (The "Alternative" Plan)**

When you have two clear paths—one for "Yes" and one for "No"—we use `else`.

![python-if-else-statement.png](/.eraser/nCNUkO1k04QolEB0AS51___mlrANIZvmbfebVXPeDhQXqWoD3x1___python-if-else-statement_ZA489IgQWA_iXjK8lLjZK.png "python-if-else-statement.png")



**Example (Odd or Even):**

```
num = int(input("Enter a number: "))
if num % 2 == 0:
    print("This number is Even.")
else:
    print("This number is Odd.")
```
**The if-elif-else Chain (Multiple Choices)**

In many cases, like grading or a menu, there are more than two possibilities. `elif` (short for "else if") allows you to check multiple conditions in order. Python only executes the **first** true branch it finds.

![python-if-elif.png](/.eraser/nCNUkO1k04QolEB0AS51___mlrANIZvmbfebVXPeDhQXqWoD3x1___python-if-elif_r517HaSyFcIxZmeFDx3tS.png "python-if-elif.png")



**Indian Grading System Example:**

```
marks = float(input("Enter your marks (0-100): "))

if marks >= 90:
    grade = "A"
elif marks >= 80:
    grade = "B"
elif marks >= 70:
    grade = "C"
else:
    grade = "D"
    
print(f"Your Grade is: {grade}")
```
**Crucial Rule: The "Golden Rule of Indentation"**

In Python, the **indentation** (the 4 spaces/tab) at the start of a line is not just for style—it tells Python which statements "belong" to which block

- A header line always ends with a **colon (:)**.
- The code inside the `if`  or `else`  **must** be shifted to the right
### Nested conditionals:
![nested-conditionals.png](/.eraser/nCNUkO1k04QolEB0AS51___mlrANIZvmbfebVXPeDhQXqWoD3x1___nested-conditionals_qE-y9WtqCbuc8MbvmO-gg.png "nested-conditionals.png")



### Exercise
1. Input a student's marks. If the marks are 33 or above, print "Congratulations, you passed!"; else, print "Better luck next time!"
2. WAP Ask the user for a number and check if it is a multiple of 7 or not
3. Write a program to check if a number entered by the user is positive, negative, or zero.
4. ** **Movie Ticket Pricing:** **Write a program that asks for age: if Age < 5: Ticket is Free. Age 5-18: Ticket is ₹150. Age > 18: Ticket is ₹250.
5. WAP to find the greatest of 3 numbers entered by the user. (Using nested conditional and without)
6. Cricket Score Message: Ask the user to input a batsman's score. If 100 or more: Print "Century!",  If 50-99: Print "Half-Century!", If 0: Print "Duck!". Otherwise: Print "Keep Playing!"
7. Login System: Create two variables, `username`  and `password` . Ask the user for input. Print "Login Successful" only if **both** match your stored values; otherwise, print "Invalid Credentials."
8. Input a number. Print "Fizz" if the number is divisible by 3 and Print "Buzz" if the number is divisible by 5 and print "Fizz Buzz" if its divisible by both 3 and 5
### Short circuit of evaluation
When Python is processing a logical expression such as `x >= 2 and (x/y) > 2`, it evaluates the expression from **left to right**. Because of the definition of `and`, if `x` is less than 2, the expression `x >= 2` is `False` and so the whole expression is `False` regardless of whether `(x/y) > 2` evaluates to `True` or `False`.  This behaviour is called short-circuiting.

### Functions (Intro)
**What is a Function?**

In programming, a **function **is a named sequence of statements that performs a specific task

**Example: **Imagine you want to make Maggi. Instead of explaining the whole 2-minute process to your brother/sister every single time, you just say, **"Make Maggi."** That single command represents a **whole set of steps** (boil water, add noodles, add masala). In Python, we create these steps once, give them a name, and then just call that name whenever we need it.

**Types of Functions**

1. **Built-in Functions:** These come pre-installed with Python (like the default apps on your phone). Examples: `print()` , `len()` , `type()` , and `range()` .
2. **User-defined Functions:** These are "Custom Apps" you build yourself using the `def`  keyword
**How to Build a Function (Syntax)**

To create a function, we use the `def` (definition) keyword:

```
def greet_student():  # This is the Header
  # This indented part is the Body
  print("Namaste! Welcome to the Python Class.")
```
- **Header:** Starts with `def` , followed by the function name, parentheses `()` , and a colon `:` .
    - Note the the function naming rules are similar to variable naming rules, Use snake_case for function naming. Function names are case sensitive, Python treats `my_func()`, `My_Func()`, and `MY_FUNC()` as three entirely different functions.

- **Body:** The actual code that runs, which **must** be indented (usually 4 spaces)
**Parameters & Arguments (The "Inputs")**

Sometimes a function needs specific information to work.

- **Parameters:** The variable names inside the parentheses in the `def`  line (the placeholders).
- **Arguments:** The actual values you pass into the function when you call it.
**Example: The Personal Greeter**

```
def say_hello(name): # 'name' is the parameter
    print(f"Hello {name}, kaise ho?")
say_hello("Aryan") # "Aryan" is the argument
```
**The return Statement (The "Output")**

Some functions just perform an action (Void functions), but others give you a result back (Fruitful functions). We use the `return` keyword to send a value back to the caller.

**Indian Context: Currency Converter (USD to INR)**

```
def convert_to_inr(usd_amount):
    inr_value = usd_amount * 93.5 # Example exchange rate
    return inr_value

pocket_money_inr = convert_to_inr(10)
print(f"Your pocket money in INR is: {pocket_money_inr}")
```
**Variable Scope: **

- **Local Scope:** Variables created **inside** a function "live" and "die" there. Other parts of the program cannot see them.
- **Global Scope:** Variables created **outside** functions are accessible everywhere
**Why Use Functions?**

1. **Avoid Repetition:** Write once, use 100 times.
2. **Better Organization:** Makes a long program easier to read and debug.
3. **Easy Collaboration:** One person can write a function for "Area" while another writes one for "Perimeter," and you can assemble them later
### Exercise (Functions)
1. Write a function called `greet()`  that takes a `name`  and a `time_of_day`  (like "Morning" or "Evening") and prints a custom greeting like "Good Morning, Rahul!".
2. Write a function `circle_area(radius)`  that calculates and returns the area.




<!--- Eraser file: https://app.eraser.io/workspace/nCNUkO1k04QolEB0AS51 --->