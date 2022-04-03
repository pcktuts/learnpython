---
layout: page
title: Operators
permalink: /operators/
nav_order: 13
---
# Operators
Like we perform an arithmetic operation on a calculator we can perform different kinds of operations with python. Python is not limited to just arithmetic operations. 

## In Python we have these different kinds of operators
1. Arithmetic operators
1. Assignment operators
3. Comparison operators
4. Logical operators
5. Identity operators
6. Membership operators
7. Bitwise operators

We will learn about the mostly used first `6` operators here.
## 1. Arithmetic Operators

We can perform normal mathematical operations with python with values and numeric variables.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/dc6dcd5244" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Assignment Operators
We can assign values to variables using the assignment operator. Some of the commonly used ones are listed below.

| Operator        | How to use it          | Alternative syntax |
|:-------------|:------------------|:------|
| =            | x = 10                    | No alternative syntax  |
| +=           | x += 10                   | x = x + 10  |
| -=           | x -= 10                   | x = x - 10  |
| *=           | x *= 10                   | x = x * 10  |
| /=           | x /= 10                   | x = x / 10  |
| %=           | x %= 10                   | x = x % 10  |
| //=          | x //= 10                  | x = x // 10 |
| **=          | x **= 10                  | x = x ** 10 |

## Comparison Operators
Comparison Operators are used to compare two values, these are commonly used in `if else` statements which we will learn later.

**Points to note: the output of the comparison operator will be always a boolean**


| Operator        | Name         | How to use it |
|:-------------|:------------------|:------|
| ==            | Equal                    | x == y  |
| !=            | Not equal                | x != y  |
| >             | Greater than             | x > y  |
| <             | Less than                | x < y  |
| >=            | Greater than or equal to | x >= y  |
| <=            | Less than or equal to    | 	x <= y  |

## Logical Operators
We can combine multiple comparison operators with the below logical operators. Let's see how it works. In Python we have three logical operators.
1. and
2. or
3. not

## 1. `and` operator
<br>

`and` operator will return `True` only if both condtions are `True`. It has `2` operands. 

### Syntax
### `condition1 and condition2`


| condition1        | condition2         | output |
|:-------------|:------------------|:------|
| True           | True                    | True  |
| True           | False                    | False  |
| False           | True                    | False  |
| False           | False                    | False  |

### Example

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/bbe60c62f6" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## 2. `or` operator
<br>

`or` operator will return `True` if one of the statements is true. It has `2` operands. 

### Syntax
### `condition1 or condition2`


| condition1        | condition2         | output |
|:-------------|:------------------|:------|
| True           | True                    | True  |
| True           | False                    | True  |
| False           | True                    | True  |
| False           | False                    | False  |

### Example

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/6bc87abced" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## 3. `not` operator
<br>

`not` operator will reverse the result, returns `False` if the result is `True`. It has only `1` operands. 

### Syntax
### `not condition`


| condition        | output        
|:-------------|:------------------|:
| True         | False                  
| False        | True                  
               

### Example
<div class="code-example">
<iframe src="https://trinket.io/embed/python3/517252bd73" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## Membership Operators

It is used to check if a sequence is present in an object.

| Operator        | Explanation         | Example |
|:-------------|:------------------|:------|
| `in`           | Returns True if a sequence with the specified value is present in the object            | x in y  |
| `not in`           | Returns True if a sequence with the specified value is not present in the object                    | x not in y  |

## Example

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/d7b73401b9" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

