---
layout: page
title: Copy Lists
permalink: /copy-lists/
nav_order: 3
parent: More about Lists

---
# Copy List 

### You cannot copy a list simply by list2 = list1, Why?

Let's try that and see what happens

`list1` and `list2` referes to the same location in the memory so any change made to `list2` will affects `list1` as well.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/597a3d7e2b" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

### So how to copy a list? Use the inbuilt `copy()` method or we can use the `list()` constructor.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/cbe9f70845" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>