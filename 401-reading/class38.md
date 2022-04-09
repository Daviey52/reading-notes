# Class 38

## React 2

[Home](https://daviey52.github.io/reading-notes/)

React 2

Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them. You can use variables to store elements. This can help you conditionally render a part of the component while the rest of the output doesn’t change.

While declaring a variable and using an if statement is a fine way to conditionally render a component, sometimes you might want to use a shorter syntax. There are a few ways to inline conditions in JSX, explained below. You may embed expressions in JSX by wrapping them in curly braces. This includes the JavaScript logical && operator. It can be handy for conditionally including an element. Another method for conditionally rendering elements inline is to use the JavaScript conditional operator condition ? true : false.

You can build collections of elements and include them in JSX using curly braces {}.Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity. The best way to pick a key is to use a string that uniquely identifies a list item among its siblings. Most often you would use IDs from your data as keys:

In React, sharing state is accomplished by moving it up to the closest common ancestor of the components that need it. This is called “lifting state up”.

Some components don’t know their children ahead of time. This is especially common for components like Sidebar or Dialog that represent generic “boxes”. We recommend that such components use the special children prop to pass children elements directly into their output:
