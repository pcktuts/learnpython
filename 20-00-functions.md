---
layout: page
title: Functions
permalink: /functions/
nav_order: 20
has_children: true


---
# Functions
So far we have used code which is executed when we run a program and used some of the inbuilt Python functions.

**Functions are block of code which are executed only when it is called.**
## Properties of functions
* Every function has a unique name
* We can pass optional parameters(inputs) to a function
* Functions can `return` a data which can be used in the program

Functions can be created with the keyword `def`. Let's see a sample function below.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/1034ca6e7a" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>


## Arguments or function params or just `args` in Python docs
The inputs that we pass to a function are generally called arguments. Arguments are optional. You can pass multiple arguments to a function. Let's see an example function which accepts some arguments.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/1cf659c256" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>


## Arbitrary Arguments, *args

If you add a `*` before the argument name in a function you can pass any number of arguments to that function which can be accessed with it's index.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/66a7d38981" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Keyword Arguments 
We can also pass named params to a function like `key = value`

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/bfac14487e" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Arbitrary Keyword Arguments, **kwargs

If you use double asterik `**` in a function param, you can pass any number of keyword arguments to a function.


<div class="code-example">
<iframe src="https://trinket.io/embed/python3/51e7b51c7c" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Default Parameter Value

We can set a default value for a function param. If we do not pass the value while we call that function, then the default value will be called.


<div class="code-example">
<iframe src="https://trinket.io/embed/python3/1e2c14073f" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Function returning a value
We can use function to return a value using the `return` keyword. The returned data can be used later in the program. Returned value is not printed unless you print it.


<div class="code-example">
<iframe src="https://trinket.io/embed/python3/669ed039b6" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## pass in functions

We can also use `pass` keyword in functions which can skip the function definition.



<div class="code-example">
<iframe src="https://trinket.io/embed/python3/07a48200c6" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>






















