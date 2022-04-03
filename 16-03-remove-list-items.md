---
layout: page
title: Remove list items
permalink: /remove-list-items/
nav_order: 3
parent: Lists
---
# Remove List items
We can remove list items in various ways.

* Remove an item by it's value
* Remove an item by it's index position

## Remove an item by it's value

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/36be37744a" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

### What happens if value is not in the list?
Python will throw an error.

error
{: .label .label-red }

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/dfe0217c42" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>


## Remove an item by it's index position

This can be done in two ways.
1. using inbuilt `pop()` method.
1. using `del` keyword.


## `pop()`
If the specified index doesn't exist `pop()` will throw an error.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/d36dffb07c" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

If we do not provide an index position to `pop()`, It will remove the last item in the list.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/cd9d9cbe78" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## `del`

<br>
Using `del` we can either delete a single item in the list or we can delete the entire list from the memory.

### Delete a single item with `del`

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/82d4dc559f" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

### Delete the entire list `del`

error
{: .label .label-red }

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/8a766dd69e" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>