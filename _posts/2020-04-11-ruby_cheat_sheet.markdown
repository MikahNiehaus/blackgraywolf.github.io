---
layout: post
title:      "Most utilized Ruby Notes"
date:       2020-04-11 16:55:44 -0400
permalink:  ruby_cheat_sheet
---


Ruby is an interpreted, high-level, general-purpose programming language.
Class method provide functionality to a class itself you cannot directly call a class method on an instance. Class method is a method that resides at the class level
instance method provides functionality to one instance of a class, you cannot call an instance method on the class itself instance method is a method that resides at the object level
both are Objects,
•	Class variable (@@a_variable): Available from the class definition and any sub-classes. Not available from anywhere outside.
•	Instance variable (@a_variable): Available only within a specific object, across all methods in a class instance. Not available directly from class definitions.
•	Global variable ($a_variable): Available everywhere within your Ruby script.
•	Local variable (a_variable): It depends on the scope. You’ll be working with these most and thus encounter the most problems, because their scope depends on various things.

self keyword refers to the class itself
a method always return exactly one single thing (an object).
Instance instance variables work on classes, classes are instances themselves (instances of class Class)
Class methods you define as class methods only exist in the object that defined them (the class) and nowhere else.
.New initializes an instance
when you call new it will create a new instance of the class, and call initialize on it, passing the same argument list, which is the input.
you create a new instance of a class by the way of calling the method new on that class, you also say that you “instantiate” that object: By calling .new you instantiate a new object. Witch is an instance

