---
layout: page
title: Transforming Strings
permalink: /transforming-strings/
nav_order: 2
parent: Strings

---
# Transforming Strings
We can transform strings using the inbuilt functions in python. Some of the commonly used string functions are listed below.

<iframe src="https://trinket.io/embed/python3/286fb0ca45" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

In Python strings are **immutable** means once you define it you cannot change it. If you try to change it directly it will result in an error.
<iframe src="https://trinket.io/embed/python3/6eb3bbd9ad" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

One possible solution is to create new variable and change it something like this
<iframe src="https://trinket.io/embed/python3/52712c415c" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## If strings are immutable how python's inbuilt functions are able to change it?
Let's dig deeper and understand it. Any variable that you create in Python has a **`unique id`**. We can use the inbuilt method called **`id()`** to find it's id. It is the memory memory address of that variable.
<iframe src="https://trinket.io/embed/python3/143da0b42e" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>



## Why strings are immutable in Python?
In Python, strings are made immutable so that programmers cannot alter the contents of it accidently. This will helps to write cleaner code with lesser bugs.
