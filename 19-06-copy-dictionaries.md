---
layout: page
title: Copy Dictionary
permalink: /copy-dictionary/
nav_order: 6
parent: Dictionaries

---
# Copy Dictionary
We cannot directly copy a dict by `dict1 = dict2` because `dict2` is pointing to `dict1` so changes in `dict1` will affect `dict2` as well.

We can copy a dict in 2 ways.
* `copy()` method
* `dict()` method

## `copy()` method

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/c07303fc23" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## `dict()` method

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/497569d96a" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>