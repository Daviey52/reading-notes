# Class 42

## Pythonism

[Home](https://daviey52.github.io/reading-notes/)

Dunder methods let you emulate the behavior of built-in types. For example, to get the length of a string you can call len('string').

Object Representation
__repr__: The “official” string representation of an object. This is how you would make an object of the class. The goal of __repr__ is to be unambiguous.
__str__: The “informal” or nicely printable string representation of an object. This is for the enduser.
You can make an object callable like a regular function by adding the __call__ dunder method.

In the __init__ method we link each RepeaterIterator instance to the Repeater object that created it. That way we can hold on to the “source” object that’s being iterated over.
In RepeaterIterator.__next__, we reach back into the “source” Repeater instance and return the value associated with it.

Generally it’s a good idea to use the built-in facade functions rather than directly accessing the dunder methods implementing a protocol. It just makes the code a little easier to read.
Python iterators normally can’t be “reset”—once they’re exhausted they’re supposed to raise StopIteration every time next() is called on them. To iterate anew you’ll need to request a fresh iterator object with the iter() function.

Python iterators normally can’t be “reset”—once they’re exhausted they’re supposed to raise StopIteration every time next() is called on them. To iterate anew you’ll need to request a fresh iterator object with the iter() function.
