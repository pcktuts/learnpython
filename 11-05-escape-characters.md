---
layout: page
title: Escape characters
permalink: /escape-characters/
nav_order: 5
parent: Strings

---
# Escape characters
Escape characters allows us to include special characters while we print a string. To do this, simply add a backslash `\` before the character you want to escape.
<br><br><br>
In the below code we tried to print single quote `'` in the out put. But in python it has a special meaning so Python tried to close that string there because it was opened at the beginning. So now this became a syntax error.
<br>

error
{: .label .label-red }
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/91527a604e" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

<br>

## Solution: Add an escape character
When we add an escape character before a character, then python will not consider it as it's syntax. It will print it exactly as it is.

<br>
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/f410f38d85" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Adding new lines in String
We can add new lines in strings using `\n`
<br>
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/6a7d894f75" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Adding tab in String
We can add tab in strings using `\t`
<br>
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/c4b6398c0f" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## What if we want to escape `\` itself?
Suppose if we want `\` to be part of our output how we can do that?. We can put double `\\` so that first `\` will be treated as an escape character so that the second one will be printed out.
<br>
<br>
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/b90966441f" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
<br>

# Raw strings
A raw string can be used by prefixing the string with **`r`** or **`R`**, which allows for backslashes to be included without the need to escape them. 
<br><br>
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/3178d21552" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

But if `\(backslash)` comes at the end in raw string it will throw an error.
<br><br>
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/74c190f572" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>
