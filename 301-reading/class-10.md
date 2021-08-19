# Class TEN

[Home](https://daviey52.github.io/reading-notes/)

1. What is a ‘call’?
Function invocation
2. How many ‘calls can happen at once?
one
3. What does LIFO mean?
Last In First Out. First out means that the last function that gets pushed into the stack is the first to be popped out, when the function returns.
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
Example credit to: freeCodeCamp
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();

firstFunction(),
secondFunction(),
thirdFunction()
5. What causes a Stack Overflow?
A stack overflow occurs when there is a recursive function without an exit point
• JavaScript error messages

1. What is a ‘refrence error’?
This is when one tries to use a variable that is not declared
2. What is a ‘syntax error’?
This is when you have something that can not be parsed in terms of syntax.

3. What is a ‘range error’?
Happens when trying to manipulate an object with a given length and a your are trying to give it an invalid length.

4. What is a ‘type error’?
This type of error appear when the types(number, strings and so on) that you are trying to use or access are incompatible fr instance accessing a property in an undefined type of variable

5. What is a breakpoint?
This is achieved by putting a debugger statement in your code in the line you want to break

6. What does the word ‘debugger’ do in your code?
Allow you to step through your code and examine how the code is working.

Reference:

[freeCodeCamp](https://www.freecodecamp.org/news/understanding-the-javascript-call-stack-861e41ae61d4/)
[codeburst](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
