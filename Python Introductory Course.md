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
- [ ] **Iterative Logic (Part 2):** Control loops with break and continue, while loop self learning
### Part 2: Functions
- [ ] **Functions (Part 1):** Learn to write reusable "blocks of code" using def, parameters, and return.
- [ ] **Functions (Part 2):** Understand Local vs. Global scope—where your variables "live" and die.
---

## Part 1: The building blocks
### Python Interpreter: Translates human readable code to machine code
![python_interpreter.png](/.eraser/nCNUkO1k04QolEB0AS51___mlrANIZvmbfebVXPeDhQXqWoD3x1___python_interpreter_pAAWWGGYOqfGhvtwMxw9s.png "python_interpreter.png")

- [ ] Create new notebook on google collab
- [ ] Your first python program
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
**Default Parameters**

Python allows you to assign a "fallback" value to a function's parameter in its definition. If a user calls the function but forgets to provide an argument for that specific parameter, Python will automatically use the pre-assigned default value.

This is incredibly useful because it makes your functions more flexible and easier to use.

**The Concept**

When you define a function, you can set a default value in the header.

- **If an argument is passed:** Python uses the value provided by the user.
- **If no argument is passed:** Python uses the default value you set.
 -------------------------------------------------------------------------------- 

**Example: The Wedding Invitation Bot**

Imagine you are writing a program to manage dinner preferences for a wedding in Bengaluru. Most guests will prefer a "Veg" meal, so we can set that as the **default**.

```
def wedding_invite(name, meal_type="Veg"):
    print(f"Namaste {name}! You are invited to the wedding.")
    print(f"Your meal preference: {meal_type}")

# 1. Calling the function WITHOUT the second argument
# Since we didn't specify, it uses the default "Veg"
wedding_invite("Rahul") 

# 2. Calling the function WITH a specific argument
# This overrides the default value
wedding_invite("Aryan", "Non-Veg")
```
**Output:**

```
Namaste Rahul! You are invited to the wedding.
Your meal preference: Veg
--------------------
Namaste Aryan! You are invited to the wedding.
Your meal preference: Non-Veg
--------------------
```
**Another Example: Cricket Match Settings 🏏**

If you are building a cricket scoreboard app, you might want to default the number of overs to 20 (for T20) unless specified otherwise.

```
def match_details(team1, team2, overs=20, venue):
    print(f"Match: {team1} vs {team2}")
    print(f"Format: {overs} overs")

# Uses default (20 overs)
match_details("India", "Australia")

# Overrides default for an ODI (50 overs)
match_details("India", "Pakistan", 50)
```
**Important Rule to Remember**

In Python, **default parameters must come at the end **of the parameter list. You cannot have a default parameter followed by a non-default one (e.g., `def func(a=10, b)` will cause a syntax error). 

**Why Use Functions?**

1. **Avoid Repetition:** Write once, use 100 times.
2. **Better Organization:** Makes a long program easier to read and debug.
3. **Easy Collaboration:** One person can write a function for "Area" while another writes one for "Perimeter," and you can assemble them later
### Exercise (Functions)
1. Write a function called `greet()`  that takes a `name`  and a `time_of_day`  (like "Morning" or "Evening") and prints a custom greeting like "Good Morning, Rahul!".
2. Write a function `circle_area(radius)`  that calculates and returns the area.
3. Write a function that calculates the fare for the Namma Metro. Following are the rules**:**
- Input the number of stations traveled.
- If the distance is 1–2 stations, the fare is ₹15.
- If the distance is 3–5 stations, the fare is ₹25.
- If the distance is more than 5 stations, the fare is ₹25 + ₹5 for every additional station
### **Iterative Logic (Part 1) — The for Loop & range()**
#### Why do we need Loops?
Imagine your teacher asks you to write "I will not talk in class" 100 times in your notebook. It’s boring, tiring, and your hand will hurt! 😫 

Computers, however, are built for **repetitive tasks**. They don't get bored and they never make mistakes while repeating things. In Python, we use **Loops **to tell the computer to perform a set of instructions over and over again.

#### The for Loop (The "Definite" Loop)
A `for` loop is used when you have a **definite** set of things to go through—like a list of your friends, a string of text, or a specific range of numbers.

**The "Sweets Distribution" Analogy:**

Imagine you have a box of 10 chocolates (a list) and you want to give one to each friend. You go to the first friend, give a chocolate, then the second, then the third, until the box is empty.

- The **box** is your sequence.
- The **action** (giving chocolate) is the code inside the loop.
**Syntax:**

```
for item in sequence:
# Code to repeat for every item
```
- **for** and **in** are Python keywords.
- **item** is the **iteration variable** that changes its value in every step.
- Example: for item in [1, 2, 3], here the value of item will change with every loop iteration
- Note that you can even iterate over a string like: 
```
for letter in "oxygen":
  print(letter)
```
#### Exercise:
1. You are given a list of numbers. Use a `for`  loop to iterate through this list and print only the numbers that are **multiples of both 3 and 5**
2. Find palindromes in the list of words: `words = ["anna", "level", "python", "racecar", "cricket"]` . Hint: You can reverse a string using this syntax: word[::-1]
3. Make a function called even_sum that takes a list of numbers and returns the sum of all even numbers present in that list
4. Given a list of cricket scores, write a program to find the highest score
5. Calculate the value of 2 to the power of 1000. Then, convert this massive number into a **string** and use a `for`  loop to iterate through every digit and calculate their total sum
6. Ask user to input their name. Use a `for`  loop to iterate through the name and **count how many vowels** (a, e, i, o, u) it contains.
#### ** **The  range() Function: The sequence or iterator for your for loop
The `range()` function is the most common way to control how many times a `for` loop runs. It

generates a sequence of numbers.

**The Three Ways to use  range() fn:**

1. **range(stop)**: Starts at 0 and goes up to (but **not including**) the stop number.
    - `range(5)`  → `0, 1, 2, 3, 4` 

2. **range(start, stop)**: Starts at your chosen number and stops before the stop number.
    - `range(1, 5)`  → `1, 2, 3, 4` 

3. **range(start, stop, step)**: Starts at `start` , stops before `stop` , and jumps by the `step`  amount.
    - `range(1, 10, 2)`  → `1, 3, 5, 7, 9`  (Great for odd numbers!)

**⚠️ Important Rule: **Range fn always stops **one step before** the final number you give it

#### Exercise:
1. Write a program to take a number between 1 to 100 from the user and then print its multiplication tables.
2. The Countdown:  Write a program using `range()` that prints a countdown from 10 to 1, and then prints "Lift-off!! "
3. Sum of Natural Numbers: Ask the user for a number `n`. Calculate the sum of all numbers from 1 to `n`. (e.g., if `n=5`, result is `1+2+3+4+5 = 15`)
4. The Even Numbers Club: Write a loop that prints all "even numbers" between 1 and 20.
5. FizzBuzz for all numbers from 1 to 1000
6. Write a program to calculate:
    1. The **sum of the squares** of the first 100 natural numbers `﻿(1^2 + 2^2 + 3^2 + ....)` 
    2. The **square of the sum** of the first 100 natural numbers ((1+2+...)^2).
    3. Print the difference between these two values

7. Write a program to find the **factorial of 100** (100!) using a `for`  loop
### Iterative Logic (Part 2)
We can control the execution of the code inside a loop using the `break` and `continue` statements in python.

- break ==> terminating a loop completely
- continue ==> skipping the rest of the current iteration
**Exercise:**

1. Your class has roll numbers from 1 to 20. However, roll numbers 5, 12, and 18 are absent today. Write a `for`  loop that prints "Roll number X is present" for everyone **except** those three numbers.
2.  Create a list of 10 random numbers (e.g., `[14, 25, 7, 49, 64, 81, 100...]` ). Write a loop to search for the number **7**. As soon as the number 7 is found, print "Lucky number found!" and stop the search immediately.
3. Write a program that calculates the sum of all numbers from 1 to 50, but skip the numbers that are multiples of 5
#### while loop (intro):
while loop is used when you don't know how many times you have to iterate, i.e. you don't have a sequence of numbers/strings before hand to use as a loop

- Keeps running as long as a condition is **True**
- **break**: Used to exit the loop immediately, even if the condition is still true. Useful for "searching" for something and stopping once found.
- **continue**: Skips the rest of the current iteration and jumps straight back to the top of the loop to start the next one
**Exercise**

1. Write a program that asks the user to enter their favorite Indian street food items one by one. The loop should run until the user types the word **"Done"**. Once "Done" is entered, the program should stop asking and print "Order finalized!"
2.  Create a variable `correct_pin = "1234"` . Write an infinite loop that keeps asking the user to "Enter your PIN."
    - If the user enters the correct PIN, print "Access Granted" and stop.
    - If they enter the wrong PIN, the loop should continue asking.

3. "Kirana" Bill Generator ==> Use a `while True` loop to repeatedly ask the user to enter the price of an item.
    - If the user enters `0`  , use the `break`   statement to stop the loop.
    - Maintain a "Running Total" (accumulator) of all prices entered.
    - At the end, apply a 5% discount if the total bill is above ₹1000

## Further learning roadmap
### Data structures and Modules
- [ ] **Lists:** Dive into Python’s most versatile "storage box." Learn indexing, slicing (accessing parts of a list), and common methods like append() and sort().
- [ ] **Dictionaries & Tuples:** Store "Key-Value" pairs (like a student’s roll number and name) and learn about Immutability with Tuples.
- [ ] **Introduction to Modules:** Use Python’s built-in libraries like math for complex calculations and random to build a "Dice Simulator" for board games.
- [ ] **Weekend Practise**: Practise of Functions and modules in python with real world application examples.
### Part 3: Real-World Data 
- [ ] **Exception Handling:** Make your code "crash-proof" using try and except to handle user errors gracefully.
- [ ] **File Handling:** Learn how Python reads from and writes to .txt files so your data is saved even after you turn off the computer.
- [ ] **CSV & Persistence:** Manage data in Excel-like formats using the csv module.
- [ ] **Introduction to NumPy:** Transition from Lists to Arrays. Think of NumPy as "Excel on Steroids" for Python.
- [ ] **Weekend Mini Project:** 
    - [ ] Build a "Student Record System" that permanently saves names and marks to a file. 
    - [ ] Analyze IPL cricket data using basic NumPy arrays.

### Part 4: Object-Oriented Programming and Debugging
- [ ] **OOP Basics:** Introduction to Object-Oriented Programming. Learn how to use "Classes" as blueprints to create "Objects".
- [ ] **OOP Continued...**
- [ ] **Debugging:** Learn how to read Tracebacks (error messages) and debug your code.
### Part 5: Ask me Anything session and Intro to python applications 🎓
- [ ] **FastAPI demo**




<!--- Eraser file: https://app.eraser.io/workspace/nCNUkO1k04QolEB0AS51 --->