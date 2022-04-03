---
layout: page
title: Accepting User input
permalink: /accepting-user-input/
nav_order: 15
---
# Accepting User input
While creating real applications we need to accept input from a user and perform calculations based upon that input. In Python we can use the inbuilt function called `input()` for that.

Let's try asking some basic informations from a user.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/e33168135c" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## `input()` always returns a string
No matter whether you typed a number or string the default data type of all the inputs are always a string. We can use the explicit type casting if we want to convert it. Let's prove it from the below example.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/22c0678154" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>