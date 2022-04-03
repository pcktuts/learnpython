---
layout: page
title: Variables
permalink: /variables/
nav_order: 6
has_children: true
---
# Variables
## What is a variable?
Variables are used to store a value. A variable can have a name and it's value. We can access the value with the name of the variable.
How to declare a variable in python
```python
message = "We are learning Python"
```
Here `message` is the name of the variable and `We are learning Python` is the value of the variable. A variable can store multiple types of data such as `strings`, `integers`, `floating point numbers` etc.
## Why we need variables?
Consider this example where we print the message Hello world 4 times
```python
print("Hello world")
print("Hello world")
print("Hello world")
print("Hello world")
```
What if we need to change the word `world` with some other word say `Python` as per our current understanding we need to modify it in 4 places to make it work. It breaks the fundamental princple of software development called `DRY`.

## What is DRY ?
**It means do not repeat yourself**
The DRY principle is stated as "Every piece of knowledge must have a single, unambiguous, authoritative representation within a system".

Let's try our original code with variables.
```python
message = "Hello World"
print(message)
print(message)
print(message)
print(message)
```
Now if we need to change the `World` we need to change at only one single place where we declared the variable. This code is easy to manage compared to the previous one.

