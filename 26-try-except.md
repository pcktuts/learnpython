---
layout: page
title: Try Except - Exception Handling 
permalink: /try-except/
nav_order: 26



---
# Try Except - Exception Handling
When an error occurs or technically we call it an exception, Python will throw an error message and application will exit. But in real applications even if error occurs we need to continue the working of the application. We can use `try` blocks for handling such kind of situations.

There are 3 blocks of code
* `try` block we can write the code which may run or fail.
* `except` block will handle the error, code inside this block will be executed when an error occurs.
* `finally` This block is optional and will be always executed whether we had an error or not.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/6fc0c0c1e4" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Handling specific kind of Exceptions

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/37669a9353" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>


## Else
We can use `else` in `try` `except` block, `else` will be executed when there are no errors.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/25ce9846a2" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>


## Finally
`finally` block will be always executed regardless of an error happended or not.This can be useful for cleaning up resources and closing objects which might use memory.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/10eaa8d3d9" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Printing exception messages

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/7d36481991" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>


## Raise an exception
We can forcefully raise an exception using the `raise` keyword.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/5735296cc0" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/1762219b4b" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

