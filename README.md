# Basic-of-Python-Programme
A collection of basic Python programs demonstrating fundamental programming concepts, including variables, data types, operators, conditional statements, loops, functions, lists, and dictionaries.

```python
with open("/mnt/data/Basic of Python Programme.md", "r") as file:
    content = file.read()

content
```



---

# Basic of Python Programme

## Variables and Data Types

1. **Variables**: Containers for storing data values.
   ```python
   x = 5
   y = "John"
   ```

2. **Data Types**: Text Type, Numeric Types, Sequence Types, Mapping Type, Set Types, Boolean Type, Binary Types.
   ```python
   x = 5
   print(type(x))  # int

   y = "Hello, World!"
   print(type(y))  # str
   ```

## Operators

1. **Arithmetic Operators**: +, -, *, /, %, **, //
   ```python
   x = 5
   y = 3
   print(x + y)  # 8
   print(x - y)  # 2
   print(x * y)  # 15
   print(x / y)  # 1.6666666666666667
   print(x % y)  # 2
   print(x ** y)  # 125
   print(x // y)  # 1
   ```

2. **Assignment Operators**: =, +=, -=, *=, /=, %=, //=, **=, &=
   ```python
   x = 5
   x += 3
   print(x)  # 8
   ```

## Conditional Statements

1. **if Statement**
   ```python
   x = 10
   if x > 5:
       print("x is greater than 5")
   ```

2. **if-else Statement**
   ```python
   x = 10
   if x > 5:
       print("x is greater than 5")
   else:
       print("x is less than or equal to 5")
   ```

## Loops

1. **for Loop**
   ```python
   fruits = ["apple", "banana", "cherry"]
   for fruit in fruits:
       print(fruit)
   ```

2. **while Loop**
   ```python
   i = 1
   while i < 6:
       print(i)
       i += 1
   ```

## Functions

1. **Defining a Function**
   ```python
   def my_function():
       print("Hello from a function")
   ```

2. **Calling a Function**
   ```python
   my_function()
   ```

3. **Function with Arguments**
   ```python
   def my_function(fname):
       print(fname + " Refsnes")

   my_function("Emil")
   ```

## Lists

1. **Creating a List**
   ```python
   mylist = ["apple", "banana", "cherry"]
   ```

2. **Accessing List Items**
   ```python
   print(mylist[0])  # apple
   ```

3. **List Methods**
   ```python
   mylist.append("orange")
   print(mylist)  # ['apple', 'banana', 'cherry', 'orange']
   ```

## Dictionaries

1. **Creating a Dictionary**
   ```python
   thisdict = {
       "brand": "Ford",
       "model": "Mustang",
       "year": 1964
   }
   ```

2. **Accessing Dictionary Items**
   ```python
   print(thisdict["model"])  # Mustang
   ```

3. **Dictionary Methods**
   ```python
   thisdict["year"] = 2018
   print(thisdict)  # {'brand': 'Ford', 'model': 'Mustang', 'year': 2018}
   ```

---

Based on this content, I'll help you create a comprehensive README file for your GitHub repository.

## README.md

```markdown
# Basic Python Programs

This repository contains basic Python programs that demonstrate fundamental concepts of Python programming, including variables, data types, operators, conditional statements, loops, functions, lists, and dictionaries.

## Table of Contents

- [Variables and Data Types](#variables-and-data-types)
- [Operators](#operators)
- [Conditional Statements](#conditional-statements)
- [Loops](#loops)
- [Functions](#functions)
- [Lists](#lists)
- [Dictionaries](#dictionaries)

## Variables and Data Types

1. **Variables**: Containers for storing data values.
   ```python
   x = 5
   y = "John"
   ```

2. **Data Types**: Text Type, Numeric Types, Sequence Types, Mapping Type, Set Types, Boolean Type, Binary Types.
   ```python
   x = 5
   print(type(x))  # int

   y = "Hello, World!"
   print(type(y))  # str
   ```

## Operators

1. **Arithmetic Operators**: +, -, *, /, %, **, //
   ```python
   x = 5
   y = 3
   print(x + y)  # 8
   print(x - y)  # 2
   print(x * y)  # 15
   print(x / y)  # 1.6666666666666667
   print(x % y)  # 2
   print(x ** y)  # 125
   print(x // y)  # 1
   ```

2. **Assignment Operators**: =, +=, -=, *=, /=, %=, //=, **=, &=
   ```python
   x = 5
   x += 3
   print(x)  # 8
   ```

## Conditional Statements

1. **if Statement**
   ```python
   x = 10
   if x > 5:
       print("x is greater than 5")
   ```

2. **if-else Statement**
   ```python
   x = 10
   if x > 5:
       print("x is greater than 5")
   else:
       print("x is less than or equal to 5")
   ```

## Loops

1. **for Loop**
   ```python
   fruits = ["apple", "banana", "cherry"]
   for fruit in fruits:
       print(fruit)
   ```

2. **while Loop**
   ```python
   i = 1
   while i < 6:
       print(i)
       i += 1
   ```

## Functions

1. **Defining a Function**
   ```python
   def my_function():
       print("Hello from a function")
   ```

2. **Calling a Function**
   ```python
   my_function()
   ```

3. **Function with Arguments**
   ```python
   def my_function(fname):
       print(fname + " Refsnes")

   my_function("Emil")
   ```

## Lists

1. **Creating a List**
   ```python
   mylist = ["apple", "banana", "cherry"]
   ```

2. **Accessing List Items**
   ```python
   print(mylist[0])  # apple
   ```

3. **List Methods**
   ```python
   mylist.append("orange")
   print(mylist)  # ['apple', 'banana', 'cherry', 'orange']
   ```

## Dictionaries

1. **Creating a Dictionary**
   ```python
   thisdict = {
       "brand": "Ford",
       "model": "Mustang",
       "year": 1964
   }
   ```

2. **Accessing Dictionary Items**
   ```python
   print(thisdict["model"])  # Mustang
   ```

3. **Dictionary Methods**
   ```python
   thisdict["year"] = 2018
   print(thisdict)  # {'brand': 'Ford', 'model': 'Mustang', 'year': 2018}
   ```


