# Objects

Objects can be defined as an encapsulation of variables and functions into a single entity. Objects normally get their variables ad fincutions from classes

We can create multiple different object that are of the same class with each object containing independent copies of the variables defined in the class

The __init__() is used when the class is being initiated. it assigns values to a class.

## Recursive

The typical structure of recursive algorithm is that it the current problem represents a simple case, solve it. else divide it into subproblems and apply the same strategy to them. A recursive function is defined in terms of itself through self-referential expressions. This means it is going to call itself and repeat this behaviour until some conditon is met and returns a result

The two ways to maintain state during recursion is by either by keeping the state in global scope or threading the state trough each recursive call so that the current state is part of the current call's excecution context.
