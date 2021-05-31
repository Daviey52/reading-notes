# class Ten

[Home](https://daviey52.github.io/reading-notes/)

## Reading Notes

## Chapter 10: "Error Handling & Debugging" (pp.406-427)

* To find the source of an error it is imperative to know how scripts are processsed:the order in which statements are executed.

* Every statement in a script lives in one of the tree execution context.

1. Global context - code that is in a script but not in a function
2. Function Context - code that iss being run within a function
3. Eval contect -text is executed like a code in an internal function called eval

* JavaScript interpreter processes one line of code at a time. When a statement needs data from another function, it stacks the new function on top of the current task.

* Each time a script enters a new execution context, there are two phases of activity

1. Prepare - the new scope is created and variable, functions and arguments are created
2. Execute - now it can assign values to variables, reference functions and run their code , execute statements.

* Functiond in JavaScript are said to have lexical scope, meaning they are linked to the object they were defined within.

* If you are anticipating that something in your code may cause an error, you can set up a set of statements to handle the error.

* When an Error object is created, it contain the following

1. name : type of error.
2. Description of error .
3. Name of JavaScript file .
4. Line Number of error .

* There are seven types of built-in error objects in JavaScript

1. Error - Generic error are based upon this error
2. SyntaxErro - syntax has not been followed
3. Reference - tried to reference a variable that is not declared/within scope
4. TypeError - An unexpected data type that cannont be coerced
5. RangeError - Number not in acceptable Range
6. UriErro - encodeURI(), decodedeURI(), and similar methods used incorrectly
7. EvalError - eval () function used incorrectly

* How to deal with Errors

1. Debug the script to fix errors
2. Handle errors gracefully
3. Check the number of parameters for a function, or the number of items in an array

* Useful tips when degguing a script

1. Try anthor browser
2. Add numbers - write numbers in the browser to observe which items can be logged
3. Strip it back - remove part of the code and strip it down to the minimum you need.
4. Explain the code - try explaining the code to someone else.
5. Search - Stack Overflow is a question and answer site for programmers
6. CodePlayground - you can ask about a code problem in an online forum e.g dabblet.com
7. Validation tools - there are a number of validation tools online to help in trying to find errors
