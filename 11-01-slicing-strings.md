---
layout: page
title: Slicing Strings
permalink: /slicing-strings/
nav_order: 1
parent: Strings

---
# Slicing Strings
Slicing means getting a portion of a particulr string. We can slice a string in various ways using the start `position(index)` and end `position(index)`. A string can be sliced using a **colon** `:` between the start and end index. 

```You can relate this to slicing a loaf of bread where we cut and take a portion of it.```
```bash
variable[start_index:end_index]
```
Get the characters from index `3` to index `7 (not included)`. In another way it can be think like this
* start from index `3`
* get the `4(7 - 3)` characters from index `3`
* Total number of characters in the output:   `7 - 3 = 4`
* `whitespace` is also treated as a character.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/60e67f2c38" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Slice From the beginning of a String
Get the characters from the start index to 5 (not included):
* Total number of characters: `5 - 0 = 5`
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/27d6d29ef8" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Slice to the End
If we do not provide the end position, it will slice the string upto the end of that string.
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/ae4e97e7e7" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Slicing with negative index
Here onething to note the negative indexing starts from the end of the string backwards from index position **-1**.

Let's look at the below code,
* Index `-6` is **P**
* Index `-2` is **o** which is not included
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/c890ababe3" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Reverse a string with extended slicing
Slicing syntax has supported an optional third `“step”` or `“stride”` argument. It works by doing `[begin:end:step]` - by leaving begin and end off and specifying a step of `-1`, it reverses a string.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/2e78df30ab" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

