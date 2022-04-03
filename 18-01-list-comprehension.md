---
layout: page
title: List Comprehension
permalink: /list-comprehension/
nav_order: 1
parent: More about Lists

---
# List Comprehension

We can use List comprehension to create a new list from an existing list based upon some condition with a shorter one line syntax. Let's try to understand with an example.

## Example problem : Select even numbers in a list?

### Using normal for loops

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/da05084e5e" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

### Using List Comprehension

The syntax
```
newlist = [expression for item in iterable if condition == True]
```
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/4001aa24e2" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
The original lists remain unchanged, only the new list get updated.

## Let's see one more example
Find items in a list which contains character `a` in it

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/68d3427275" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Expression
The `expression` is the current item in the iteration, which we can manupulate and it will change the final output of the list.

## Example

Here the expression part is manipulated as `x.upper()` so each item in the list will be in uppercase.
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/cb01f15f89" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

We can also use `if else` conditions in list comprehension

## Example : Hide the odd numbers in the list

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/3b457a0b5a" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
