# Class Six

[Home](https://daviey52.github.io/reading-notes/)

## Problem Domain , Objects and the DOM

### Problem Domain

* Problem Domain can be considered by some as one of the single hardest thing to learn about programming

* can be argued that by creating a familiar problem domain, learning a certain technology is much easier than learning the problem domain and also the technology

* Writing code is a lot like putting together a jigsaw puzzle. We put together code with the purpose of building componets that we have taken out of the 'bigger picture' of the problem domain.

* if understanding the problem domain is the hardest part of programming and you have an aim of making it easier, you can try 1. Making the problem domain easier 2. get better at understanding the problem domain

### Object Literals

* Object groups together a set of variables and functions to create a model of something you would recognize from the real world. In an object, variables and functions takes on new names

* An object variable becomes known as properties while a functions becomes known as a methods

* Literal notation is the easiest and most popular way to create objects

* you can access the property or methods of an object using dot notation. You can also access properties using square brackets

* The new keyword and the object constructor creates a blank object. You can then add properties and methods to the objects

### Document Object Model

* The document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the content of a web page while it is in the browser window.

* The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules. it is implimented by all major browser makers and covers two primary areas: Making a model of the HTML Page and Accesing and changig the HTML page.

* Accessing and updating the DOM tree involves

1. Locating the node that represent the element you want to work with
2. Use its text content, child element, and attributes

* Methods that find element in the DOM tree are called DOM queries. When ever you need to work with an element more than once, you should use a variable to store the result of the query.

* When people talk of storing elements in variable, they are really storing the location of the element(s) within the DOM tree in a variable. The property and methods of that element node work on the variable.

* Dom queries may return one element, or they may return a NodeList, which is a collection of nodes.

* There are two ways of selecting an element from a nodelist: The Item() method and array syntax. Both require the index number of desired elements. Normally, Array syntax is preffere over the item () method becuse it is faster.

* When you have a nodelist, you can loop through each node in the collection and apply the same statement to each.

* When you have an element node , you can select another element in relation to it using the five properties. This is known as traversing the DOM.

* DOM manupulation offer another technique to add new content to a page rather than innerHTML. It involves 

1. Create the element
2. Give it content
3. Add it to the DOM

* Different browsers offer tools for viewing the DOM tree.
