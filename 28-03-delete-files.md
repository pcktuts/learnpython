---
layout: page
title: Delete Files 
permalink: /delete-files/
nav_order: 3
parent : Files
---


## Delete Files

We can make use of the inbuilt `os` module in Python to delete files. It is always safer to check whether the file exists before deleting it.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/5a531918e7" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Remove a folder
**We can delete only empty folders**

```python
import os
os.rmdir("Downloads")
```