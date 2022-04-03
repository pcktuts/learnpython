---
layout: page
title: Remove Dictionary Items
permalink: /remove-dictionary-items/
nav_order: 4
parent: Dictionaries

---
# Remove Dictionary Items
We can remove items from a dict in several ways
* `pop()`
* `popitem()`
* `del` 
* `clear()`

Let's see how each of these works with an example

## `pop()` will remove item with a specified key name

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/82ead8ad61" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## `popitem()` will remove the last inserted item from version `3.7` before that it will be a random item.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/e32d136f7d" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## `del` keyword removes item with a specified key. It can be also used to delete the entire dict from memory as well.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/0b530cbff0" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## `clear()` empties the dict

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/fcad4a647b" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>