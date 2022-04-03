---
layout: page
title: Reassigning Variables
permalink: /reassigning-variables/
nav_order: 3
parent: Variables

---
# Reassigning Variables

In Python if you assign a variable you can change it's value whenever needed. Also you can assign different type of value to that variable. Consider the below example.
<iframe src="https://trinket.io/embed/python3/4aaa70bd3f" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
The data type such as(string, integer) also can be changed in Python when needed because Python is a dynamically typed programming lanugage. In other languages like `c` or `java` once you declare a variable as say `integer` you cannot reassign any other values other than integers. Such kind of languages are called statically typed programming languages.

Consider the example in `C` programming lanugage.

Error
{: .label .label-red }
```c
int d = 3;
d = "Hello"; // This will throw an error in C
```
Same example in Python
```python
d = 3
d = "Hello" # This is will work in Python
```