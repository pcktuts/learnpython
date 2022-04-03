---
layout: page
title: Tuples
permalink: /tuples/
nav_order: 21


---
# Tuples
Tuples are collections which are ordered and **immutable**. For tuples we use round `()` brackets.

## Syntax

```python
my_tuple = (1, 2, 3)
```
## Properties of Tuples
* Ordered, elements can be accessed using index.
* Allows duplicate elements.
* Tuples are immutable, once defined it cannot be changed.
* Type of tuple is `<class 'tuple'>` 

## Creating tuple with one item
If there is only one item in tuple we have to add a `,` after the first element otherwise it is treated as a string.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/70a0c02d0d" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Change tuple values

You cannot directly change tuples values. Let's see what will happen if we try that.


<div class="code-example">
<iframe src="https://trinket.io/embed/python3/cd33973aa7" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Workaround for changing a tuple value

Convert the tuple into a list then append values then convert it back to a tuple again.


<div class="code-example">
<iframe src="https://trinket.io/embed/python3/24a1e0bd75" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Accessing tuple items
We can access individual elements using it's index value and use for loop to print all the items.


<div class="code-example">
<iframe src="https://trinket.io/embed/python3/1d07f5fc3e" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
