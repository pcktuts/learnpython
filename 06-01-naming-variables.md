---
layout: page
title: Naming Variables
permalink: /naming-variables/
nav_order: 1
parent: Variables

---
# Naming Variables

There are some rules for defining variables
* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (message, Message and MEESAGE are three different variables)

**You don't need to by heart it, We are going to learn some naming standards.**

Some valid variable names
```python
greetmessage = "Good morning"
greet_message = "Good morning"
_greet_message = "Good morning"
greetMessage = "Good morning"
GreetMessage = "Good morning"
```
Some illegal variable names

Error, this code won't run
{: .label .label-red }
```python
greet message = "Good morning"
43greet_message = "Good morning"
greet-message = "Good morning"
```
### Assign Multiple Values
```python
a, b, c = "Python", "PHP", "Javascript"
```
In the above example value of `a` is `Python`, value of `b` is `PHP` and value of `c` is `Javascript`.

### Assign same Value to Multiple Variables

<iframe src="https://trinket.io/embed/python3/f63d63c553" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
When you write large programs or when you work as a team in a company, it is important that you must use some standards so that it will be easier for you and other team memebers to easily understand the code.

### Some of the commonly used variable naming conventions
* Snake casing

Every new word is seperated with `_`(underscores). Python uses snake casing.
```python
first_name = "John"
last_name = "David"
```
* Camel casing

Every new word starts with a Capital letter except the starting word. Javascript is built with camel casing standard.
```python
firstName = "John"
lastName = "David"
```
* Pascal casing

First letter of every word starts with a capital letter. Microsoft dot net uses this casing as their standard.
```python
FirstName = "John"
LastName = "David"
```