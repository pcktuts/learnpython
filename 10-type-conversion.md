---
layout: page
title: Type Conversion
permalink: /type-conversion/
nav_order: 10
---
# Type Conversion
Type conversion is the process of converting the data type of a value such as integer, float, string etc. There are two types of type conversion in Python.

1. Implicit Type Conversion
1. Explicit Type Conversion

## Implicit Type Conversion
This is done by the Python intrepreter. In this example we take the difference of two variable which has different data types such as `int` and `float` but python automatically converted the result data type into `float` in order to prevent the data loss.
<iframe src="https://trinket.io/embed/python3/6db44e73b1" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## Explicit Type Conversion
Explicit type conversion is also known as type casting. We as a programmer do the type conversion here. We can use some of the inbuilt functions in python to do the explicit type conversion.

<iframe src="https://trinket.io/embed/python3/3f05c7793b" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

You cannot convert all the values from one data type to another. Look at the below code. This code throws a `run time error`, and we got a partial output only.

error
{: .label .label-red }
<iframe src="https://trinket.io/embed/python3/c37dd7fb79" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

## Points to note 
* Implicit conversion is done by Python interpreter only.
* Explicit type conversion is also known as type casting.
* In Explicit type conversion you may loose some data such as if you convert a `float` into `int` you will lose the fractional part.
