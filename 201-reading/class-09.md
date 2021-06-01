# class Nine

[Home](https://daviey52.github.io/reading-notes/)

## Reading Notes

* Chapter 7: “Forms” (p.144-175)

* Chapter 14: “Lists, Tables & Forms” (pp.330-357)

* Chapter 6: “Events” (pp.243-292)

## Forms

* The best known form on the web is probably the search box that sits right in the middle of Google's homepage

* There are several types of form control that allows the collection of information from website visitors. They include allowing adding text , making choices and submitting forms.

* Information from a for is sent in name/value pairs.

* forms can be sent using one of the following methods - get ot post

* with the get method, the values from the form are added to the end of the URL specified in the action attribute. This method is idea for short forms and when just retriving data from the web server.

* with the post method, the values are sent in what is know as HTTP header, as a rule of thumb this method should be used to allow users to upload a file, when the form is very long, when the form contains sensitive data and when there is need to add information to or delete information from, a database.

* Label element can be used in two ways: wrap around both the text description and the form input or be kept separate from form control and use the for attribute to indicate which form control it is a label for.

* you can group related form control together inside the fieldset element. This is particulary helpful for longer forms.

* Legend element can come directly after opening fieldset tag and contain a caption that helps identify the purpose of that group form control.

* Validating content on a form before it is sent to the server reduces the amount of work the server has to do and enables the user to see if there are problems with the form faster than if validation were performed on the server.

## List , Tables and Forms

* List-style-type property allows user to be able to control the shape or sty;e of a bullet point. It can be used on rules that apply to the ol ul and li elements.

* By appropriately styling forms, it can make them more appealing to be filled by users. css is commonly used to control the apperance of form elements. this is both to make them more attractive and make them more consistent across different browser. It is most common to style - text inputs and text areas, submit buttons and labels on forms to get the form control to align nicely.

* Table cells can have different borders and spacing in different browsers, but there are property you can use to control thm and make them more consistent

* Forms are easier to use if the form control are vertically alligned using CSS.

## EVENTS

* Event fire or raised is when an event has occured. Events are said to trigger a function or a script.

* When users interact with HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together, these events are known as event handling

* Step one is selecting the the element node(s) you want the script to respond to

* Step two is indicate which event on the selected node(s) will trigger the response. this is normally reffered to as binding

* State the code you want to run when the event occurs

* Event handlers let you indicate which event you are waiting for on any particular element. there are three types of event handlers

1. HTML EVENT Handlers - this is a bad practise though it is important to be aware of it. This method is no longer used becuse it is better to separate the JavaScript from the HTML.
2. Traditional DOM Event Handlers - they are considered better than HTML event handler becuse they let you separate the JavaScipt from the HTML. Its major drawback is that you can only attach a single function to any event.
3. DOM Level 2 Event Listner - they were introduced in an update to the DOM back in the year 2000. they are now the favoured way of handling events. the syntax is very different and unlike traditional event handlers, they allow one even to trigger multiple functions. As a result, there are less likely to be conflicts between different scripts that run on the same page

* Event Bubbling is when an event starts at the most specific node and flows outwards to the least specific one. This is the default type of event flow with very wide browser support.

* Event Capturing is when an event starts at the least specific node and flows inwards  to the most specific one. This is not supported in Internet Explorer 8 and earier versions.

* When an event occurs, the event object tells you the information about the event and the element it happened upon.

* Creating event listners for a lot of elements can slow down a page, thpugh event flow allows you to listen for an event on a parent element

* benefits if event delegation

1. Work with new elements
2. Solve Limitations with this keyword
3. simplifies your code

* whenever elemnts are added or removed from the DOM, its struture changes. this is know as a mutation event
