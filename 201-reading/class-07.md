# Class Seven

[Home](https://daviey52.github.io/reading-notes/)

## Domain Modelling , Tables , Functions, Methods and Objects

### Domain Modelling

* Domain modeling is the process of creating a conceptual model in code for a specific problem. A model will describe various entities, their attributes and behaviours as well as the constrains that govern the problem domain. An entity that stores data in properties and encapsulates behaviour in methods is commonly refered to as an object-oriented model

* A domain model that's articulated well can verify and validate understanding of a specific problem amoung various stakeholders. When used as a communication toal, it can define a vocabulary that will be used within and between both technical and business teams.

* When modeling a single entity that will have many instances, you should build a self-contained object wu=ith the same attributes and behaviours

* Model its attributes with a constructor function that defines and initializes properties

* model its beheviours with small methods that focus on doing the job well

* create instances using the new keyword followed by a call to a constructor function

* Use this variable within methods so that they can access the object's properties and methods from inside.

### Tables

* When representing information on a table, we need to think in terms of a grid made up of rows and column. Grid allows us to understand complex data by referencing information on two axes. Each block in the grid is reffered to as a table cell

* colspan and rowspan can be used on a table to stretch across more than one row or column respectively.

* some of the HTML editors that come in conent management system offer tools that help with table drawing. If the first row of your table only contains th elements then you may find that the editor automatically inserts a thead element automatically.

### Functions, Methods and Objects

* Functions consists of a group of objects that have been grouped together becuse they perform a specific task.

* Method is the same as functions except they are created inside( and are part of an object)

* piece of information passed to a function are know as parameters

* When you write a function and expect it to provide you with an answer, the responce is known as return value.

* Functional declaration is giving a function a name and then writing statements needed to achieve its task inside the curly braces.

* In some cases a function need specific information to perform its task, in such cases, when you declare the function, you give it parameters inside the function, the parameter act like variables.

* when you call a function that has parameters, you specify the values it should use in the parentheses that follow its name. The values are called arguments and they can be provided as values or variable.

* If a function is placed where a browser expects to see an expression, it gets treated as an expresion, and this is know as a function expression.

* In a function expression, the name is normally ommited

* A functional expression is not processed until the interpreter gets to that statement. This means it can not be called before the interpreter has discovered it.

* Anonymous functions are used for code that only needs to run once within a task , rather than repeately being called by other parts of the script

* The location where you declare a variable will affect where it can be used within a code. If you declare it within a function, it can only be used within that function. This is know as the variable's scope.

* Global variable use more memory. The browser has to remember them for as long as the web page using them is loaded. Local variables are only remembered during the period of time that a function is being executed.

* Literal notation is the easiest and most popular way to create objects.

* You can access the properties or methods of an object using dot notation. You can also access properties using a square bracket.

* The keyword this is commonly used inside functions and objects, where the function is declared alters what this means. It always refers to the one object, ussualy the object in which the function operates.

* In javaScript, data is represented using name/value pairs. To organize your data, you can use an array or object to group a set of related values. In arrays and objects the name is also known as key.

* Browsers come with a set of built-in objects that represent things like the browser window and the current web page shpwn in that window. These buil-in objects act like a toolkit for creating interactive web pages.

* Browser Object model creates a model of the browser tab or window

* Bocument Object Model creates model of the current web page

* Global JavaScript Objects do not form a single model. They are a group of individual object that relate to different parts of the JavaScript language.
