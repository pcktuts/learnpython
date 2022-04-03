---
layout: page
title: Conditionals if else
permalink: /conditionals-if-else/
nav_order: 14
---
# Conditionals `if else`
Programming can be used to perform certain actions based upon certain conditions. We use `if else` statements to perform such decision making actions in a program. Understanding `if else` is really important then only you can write real world applications.

## Syntax

```python
if(boolean condition):
    #code to be executed if true
else:
    #code to be executed if false
```

Consider few real life examples
* You can apply for a license if you are 18 years old
* You can go abroad if you have a passport and a visa
* We can watch the movie if we got 2 tickets else we can go to the park

Now let's try to convert the above statements into a python program

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/c6e1a05bf0" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Golden rule in Python - Indentation
Python relies on Indentation(Whitespace) before a line to define a `scope`. Other languages uses curly brackets `{}` for that. Let's examine the difference between `if else` in `Javascript` and `Python` 

### Javascript if else
Here we use `curly {}` brackets, So space ie indentation doesn't matter, you can write code with any spaces as long as `{} brackets` are closed correctly.

```js
let x = 10;
if(x > 7) {
    console.log("x is greater");
} else {
    console.log("x is lesser");
}
```
## **In Python indendation ie space matters, below code won't run**
<br>

error
{: .label .label-red }

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/5dffa766e0" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## If we have multiple condition blocks we can use `elif`

### Some rules to note

* We can use any number of `elif` but there must be only one `else`
* `elif`, `else` are optional in a `if` statement
* Only one block of code is executed at a time
* `else` block doesn't need a condition

## Syntax
```python
if condition1:
    print("condition1 is true")
elif condition2:
    print("condition2 is true")
else:
    print("both the above conditions are false")
```
<br>
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/48740acf5f" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Nested if else

We can have `if` condition inside another `if`. Such kind of conditionals are called `nested if`

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/a0746bdc94" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## The pass Statement
`if` statement cannot be empty, but if you want to put it for empty for some reason you can use a `pass` statement.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/a39ce889ec" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Reserved Keywords
In a computer language, a reserved word (also known as a reserved identifier) is a word that cannot be used as an identifier, such as the name of a variable, function, or label – it is "reserved from use". In the above examples we have used few of them such as `if`, `else`, `elif`, `pass` and there are more, that we will learn later.

### So what is the importance of reserved keywords?
* You cannot create a variable name with one of the reserved name.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/c996aa3ab6" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>