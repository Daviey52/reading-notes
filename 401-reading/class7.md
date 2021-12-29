# Class seven

[Home](https://daviey52.github.io/reading-notes/)

## Scope

scope in programming defines an area of the programm in which you can unambigously access the names of variables, functions, objects and so on. A name is only visible to and accessible by the code in its scope.

Global scope are names that are available to all your code

local scope are names that are only available or visible to the code within the scope.

local scope contains names that you define inside a function

Enclosing scope is a special scope that only exist for nested functions.

Global scope is the top most scope in python. this scope contains all of the names that you define at the top level of a program or a module.

Built in scope is a special scope that is loaded or created whenever you run a script or open an interactive session. this scope contains names including keywords, exceptions, functions and other attributes that are built into python.

whenever you assign a value to a name in python, you create a new name and you update an existing name.

Global names can be updated or modified from any place in your global python scope.

Modfying global name is considered bad practise becuses it can lead to difficulty in debuging, hard to understand and impossible to reuse.

Built is scope is a python scope that is implimented as a standard library module named builtins.

with a global statement you can define a list of names that are going to be treated as global names.

with nonlocal statement, you can define a list of names that are going to be treated as nonlocal.
