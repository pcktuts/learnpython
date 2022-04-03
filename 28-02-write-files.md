---
layout: page
title: Write/Create Files 
permalink: /write-files/
nav_order: 2
parent : Files
---


## Write Files

We can write contents to a file in two ways. 
* `a` - Append mode - will append or add contents to then end of the file.
* `w` - Write mode - will overwrite any existing contents of the file.

## Append mode example

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/7b06ce5e0c" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Write mode example
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/9d8d8da303" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Create files
We can create files using the `open()` function by using different methods.

| mode        | description        
|:-------------|:------------------|
| x           | Create - will create a file, returns an error if the file exist 
| a | Append - will create a file if the specified file does not exist  | 
| w           | Write - will create a file if the specified file does not exist     |


<div class="code-example">
<iframe src="https://trinket.io/embed/python3/42224f517b" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>