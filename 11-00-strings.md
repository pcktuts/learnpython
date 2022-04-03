---
layout: page
title: Strings
permalink: /strings/
nav_order: 11
has_children: true
---
# Strings
Strings are sequence of characters surrounded by either single quotation marks `'`, or double quotation marks`"`.
You can display a string using pythons inbuilt function called `print()`. In the below code we have used both single quotes and double quotes both are the same.

**Note the output doesn't contain a single quote or double quote.**
<iframe src="https://trinket.io/embed/python3/f9a5652e6d" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## What if you want to include the quotes in the output?

You can use double quotes and single quotes interchangably for that. Let's look at the below example.
<iframe src="https://trinket.io/embed/python3/6b592b835a" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## Create a string variable
<iframe src="https://trinket.io/embed/python3/56fe2d39ae" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## Multi line strings
You can also create multi line strings in python and assign it to a variable. Here we can use tripple double quotes `"""` or tripple single quotes `'''` for that. Let's see the example below.

<iframe src="https://trinket.io/embed/python3/56a3d1ef7b" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## Individual characters in a string can be accessed via `index`
### So what is an index?
Index for a string simply means the position of a particular character in a string. There is one important rule in programming that is,
**Index(or position) starts from `0` not from `1`**. Let's understand what it actually means by the below example.
```python
greeting = "Hi lpm"
```

| Index 0      | Index 1  | Index 2 | Index 3 | Index 4 |Index 5 |
|:-------------|:---------|:------|:------|:------|:------|
| H           | i         | `whitespace` | l | p | m

Index can be accessed by using the square bracket `[]` syntax like this.
To get the total number of characters in a string you can use Pythons inbuilt method called `len()`.
## Points to note here
* The length of the string `greeting` is `6`
* So the maximum index value will be `5` since index starts from `0`
<iframe src="https://trinket.io/embed/python3/69dda96cb2" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

If you try to print an index which doesn't exists you will get an error.

error
{: .label .label-red }
<iframe src="https://trinket.io/embed/python3/fb296187a0" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>