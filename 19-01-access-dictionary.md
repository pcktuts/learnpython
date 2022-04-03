---
layout: page
title: Access Dictionary Items
permalink: /access-dictionary-items/
nav_order: 1
parent: Dictionaries

---
# Access Dictionary Items
We can access dict items in 2 ways.
* Using key name
* using `get()` method

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/5fa7f89f50" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## What happens if key doesn't exists
Python will throw an error

error
{: .label .label-red }

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/d6c9fb776a" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Print all keys in a dict
Using the `keys()` method we can print all the keys in a dict.
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/63aa34f988" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Print all items in a dict
Using the `items()` method we can get each items in a dict as a `tuple`
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/2bbacd701c" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Check if a keys exists in a dict
We can use `in` operator to check if a keys exists in a dict. This is a good practice before accessing dict so that we can avoid the error.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/ade23345c3" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
