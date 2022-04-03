---
layout: page
title: Meaningful Variables
permalink: /meaningful-variables/
nav_order: 2
parent: Variables

---
# Meaningful Variables

Look at the below code and uderstand how we can write meaningful variable names which will helps to understand the code better.

Bad practice
{: .label .label-red }
```python
p = "Krishna"
x = 25
j = "test@test.com"
```
The above code is a valid python code but it is hard to understand what it really means. Let's re write the code in such a way that it is easier for everyone to understand.

Good practice
{: .label .label-green }
```python
name = "Krishna"
age = 25
email = "test@test.com"
```
In real projects a file may contain hundreds or thousands of lines where 
it will be difficult to understand names such as `p, x, j` but names such as `name, age, email` are easier to understand.