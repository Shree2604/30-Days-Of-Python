<div align="center">
  <h1>Introduction</h1>
</div>


  - [Introduction](#introduction)
  - [Why Python ?](#why-python-)
  - [Basic Python](#basic-python)
    - [Python Syntax](#python-syntax)
    - [Python Indentation](#python-indentation)
    - [Comments](#comments)
    - [Data types](#data-types)
      - [Number](#number)
      - [String](#string)
      - [Booleans](#booleans)
      - [List](#list)
      - [Dictionary](#dictionary)
      - [Tuple](#tuple)
      - [Set](#set)
    - [Checking Data types](#checking-data-types)
    - [Python File](#python-file)
  - [💻 Exercises - Day 1](#-exercises---day-1)
    - [Exercise: Level 1](#exercise-level-1)
    - [Exercise: Level 2](#exercise-level-2)
    - [Exercise: Level 3](#exercise-level-3)


## Introduction

Python is a high-level programming language for general-purpose programming. It is an open source, interpreted, objected-oriented programming language. Python was created by a Dutch programmer, Guido van Rossum. The name of Python programming language was derived from a British sketch comedy series, *Month Python's Flying Circus*.  The first version was released on February 20, 1991.

## Why Python ?

It is a programming language which is very close to human language and because of that it is easy to learn and use.
Python is used by various industries and companies (including Google). It has been used to develop web applications, desktop applications, system adminstration, and machine learning libraries. Python is highly embraced language in the data science and machine learning community. I hope this is enough to convince you to start learning Python. Python is eating the world and you are killing it before it eats you.


Let us do some maths first before we write any Python code:

- 2 + 3 = 5
- 3 - 2 = 1
- 3 \* 2 = 6
- 3 / 2 = 1.5
- 3 ^ 2 = 3 x 3 = 9

In python we have the following additional operations:

- 3 % 2 = 1 => which means finding the remainder
- 3 // 2 = 1 => which means removing the remainder

Let us change the above mathematical expressions to Python code. The Python shell has been opened and let us write a comment at the very beginning of the shell.

A _comment_ is a part of the code which is not executed by python. So we can leave some text in our code to make our code more readable. Python does not run the comment part. A comment in python starts with hash(#) symbol.
This is how you write a comment in python

```shell
 # comment starts with hash
 # this is a python comment, because it starts with a (#) symbol
```

![Maths on python shell](./images/maths_on_python_shell.png)

Before we move on to the next section, let us practice more on the Python interactive shell. Close the opened shell by writing _exit()_ on the shell and open it again and let us practice how to write text on the Python shell.

![Writing String on python shell](./images/writing_string_on_shell.png)


## Basic Python

### Python Syntax

A Python script can be written in Python interactive shell or in the code editor. A Python file has an extension .py.

### Python Indentation

An indentation is a white space in a text. Indentation in many languages is used to increase code readability, however Python uses indentation to create block of codes. In other programming languages curly brackets are used to create blocks of codes instead of indentation. One of the common bugs when writing python code is wrong indentation.

![Indentation Error](./images/indentation.png)

### Comments

Comments are very important to make the code more readable and to leave remarks in our code. Python does not run comment parts of our code.
Any text starting with hash(#) in Python is a comment.

**Example: Single Line Comment**

```shell
    # This is the first comment
    # This is the second comment
    # Python is eating the world
```

**Example: Multiline Comment**

Triple quote can be used for multiline comment if it is not assigned to a variable

```shell
"""This is multiline comment
multiline comment takes multiple lines.
python is eating the world
"""
```

### Data types

In Python there are several types of data types. Let us get started with the most common ones. Different data types will be covered in detail in other sections. For the time being, let us just go through the different data types and get familiar with them. You do not have to have a clear understanding now.

#### Number

- Integer: Integer(negative, zero and positive) numbers
    Example:
    ... -3, -2, -1, 0, 1, 2, 3 ...
- Float: Decimal number
    Example
    ... -3.5, -2.25, -1.0, 0.0, 1.1, 2.2, 3.5 ...
- Complex
    Example
    1 + j, 2 + 4j

#### String

A collection of one or more characters under a single or double quote. If a string is more than one sentence then we use a triple quote.

**Example:**

```py
'Shreeraj'
'Finland'
'Python'
'I love teaching'
'I hope you are enjoying the first day of 30DaysOfPython Challenge'
```

#### Booleans

A boolean data type is either a True or False value. T and F should be always uppercase.

**Example:**

```python
    True  #  Is the light on? If it is on, then the value is True
    False # Is the light on? If it is off, then the value is False
```

#### List

Python list is an ordered collection which allows to store different data type items. A list is similar to an array in JavaScript.

**Example:**

```py
[0, 1, 2, 3, 4, 5]  # all are the same data types - a list of numbers
['Banana', 'Orange', 'Mango', 'Avocado'] # all the same data types - a list of strings (fruits)
['Finland','Estonia', 'Sweden','Norway'] # all the same data types - a list of strings (countries)
['Banana', 10, False, 9.81] # different data types in the list - string, integer, boolean and float
```

#### Dictionary

A Python dictionary object is an unordered collection of data in a key value pair format. 

**Example:**

```py
{
'first_name':'Shree',
'last_name':'Raj',
'country':'Finland', 
'age':250, 
'is_married':True,
'skills':['JS', 'React', 'Node', 'Python']
}
```

#### Tuple

A tuple is an ordered collection of different data types like list but tuples can not be modified once they are created. They are immutable.

**Example:**

```py
('Shree', 'Paul', 'Brook', 'Abraham', 'Lidiya') # Names
```

```py
('Earth', 'Jupiter', 'Neptune', 'Mars', 'Venus', 'Saturn', 'Uranus', 'Mercury') # planets
```

#### Set

A set is a collection of data types similar to list and tuple. Unlike list and tuple, set is not an ordered collection of items. Like in Mathematics, set in Python stores only unique items.

In later sections, we will go in detail about each and every Python data type.

**Example:**

```py
{2, 4, 3, 5}
{3.14, 9.81, 2.7} # order is not important in set
```

### Checking Data types

To check the data type of certain data/variable we use the **type** function. In the following terminal you will see different python data types:

![Checking Data types](./images/checking_data_types.png)

### Python File

First open your project folder . If you don't have this folder, create a folder. Inside this folder, create a file called helloworld.py. Now, let's do what we did on python interactive shell using visual studio code.

The Python interactive shell was printing without using **print** but on visual studio code to see our result we should use a built in function *print(). The *print()* built-in function takes one or more arguments as follows *print('arument1', 'argument2', 'argument3')*. See the examples below.

**Example:**

The file name is helloworld.py

```py
Challenge

print(2 + 3)             # addition(+)
print(3 - 1)             # subtraction(-)
print(2 * 3)             # multiplication(*)
print(3 / 2)             # division(/)
print(3 ** 2)            # exponential(**)
print(3 % 2)             # modulus(%)
print(3 // 2)            # Floor division operator(//)

# Checking data types
print(type(10))          # Int
print(type(3.14))        # Float
print(type(1 + 3j))      # Complex number
print(type('Asabeneh'))  # String
print(type([1, 2, 3]))   # List
print(type({'name':'Asabeneh'})) # Dictionary
print(type({9.8, 3.14, 2.7}))    # Set
print(type((9.8, 3.14, 2.7)))    # Tuple
```



🌕  You are amazing. you are on your way to greatness. Now do some exercises for your brain and muscles.

## 💻 Exercises - Day 1

### Exercise: Level 1

1. Check the python version you are using
2. Open the python interactive shell and do the following operations. The operands are 3 and 4.
   - addition(+)
   - subtraction(-)
   - multiplication(\*)
   - modulus(%)
   - division(/)
   - exponential(\*\*)
   - floor division operator(//)
3. Write strings on the python interactive shell. The strings are the following:
   - Your name
   - Your family name
   - Your country
   - I am enjoying 30 days of python
4. Check the data types of the following data:
   - 10
   - 9.8
   - 3.14
   - 4 - 4j
   - ['Asabeneh', 'Python', 'Finland']
   - Your name
   - Your family name
   - Your country

### Exercise: Level 2

1. Create a folder named day_1 . Inside day_1 folder, create a python file helloworld.py and repeat questions 1, 2, 3 and 4. Remember to use _print()_ when you are working on a python file. Navigate to the directory where you have saved your file, and run it.

### Exercise: Level 3

1. Write an example for different Python data types such as Number(Integer, Float, Complex), String, Boolean, List, Tuple, Set and Dictionary.
2. Find an [Euclidian distance](https://en.wikipedia.org/wiki/Euclidean_distance#:~:text=In%20mathematics%2C%20the%20Euclidean%20distance,being%20called%20the%20Pythagorean%20distance.) between (2, 3) and (10, 8)

🎉 CONGRATULATIONS ! 🎉
