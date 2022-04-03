---
layout: page
title: Object Oriented Programming 
permalink: /object-oriented-programming/
nav_order: 24
has_children: true



---
# Object Oriented Programming

This one of the most important concepts in any programming language. We need to understand the below two concepts to start coding in oops way.

* Class
* Objects

A class is like a blueprint from which we can create any number of objects. We can relate this to a real world objects like Car.

For a class `Car` we can have multiple objects like

* Swift
* Corolla
* Polo

Class Car is just a blueprint only. It can have attributes like
* color
* mileage
* fuel

Individual objects like Swift, Corolla & Polo has the actual values for these attributes like a blue swift car has a milege of 14 and it is a petrol car.

We can use/create objects only after creating the class. A class can contain methods/functions which can be called/invoked using an object only.

Let's see the actual code example below.

<div class="code-example">
<iframe src="https://trinket.io/embed/python3/fca693b5fa" width="100%" height="356" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>
</div>

## `__init__()`
This is a special method inside a class. It is known as a constructor. This method is automatically executed when we create an object. So we can use constructor to initialize values which are required in a class.

## self
The self means the current instance or the current object. In the above examples the objects are `swift_object` and `toyota_object`. Since objects are created after we create the class, the class variables are represented as `self.variablename` because we do not have an object name inside a class so we represent it as `self`. In other programming languages `self` is also known as `this` for example in `php` or `javascript`.