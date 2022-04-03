---
layout: page
title: Loops
permalink: /loops/
nav_order: 17
has_children: true

---
# Loops 

In computer science, a loop is a programming structure that repeats a sequence of instructions until a specific condition is met.

## In Python we have 2 kind of loops
1. `while` loop
1. `for` loop

## While loop

A `while` loop is executed as long as a condition is `True`.

### Syntax

```python
while(boolean condition):
    # statements to be executed if condition is true
```
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/d2ab01582e" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>


## for loop

We can use `for` loop to iterate over a sequence of items such as (strings, lists, tuples, dict etc).

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/dc923eea3e" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

### We can Loop over strings like this

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/6c4e1dffa9" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## range() Function

We can use the this inbuilt `range()` function to loop through a block of code specified number of times. It has 3 parameters using that we can customise the output. All the parameters are integers.

### Syntax

```python
for x in range(start, stop, step):
    print(x)
```

<br>
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/0f70e272d6" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>