# class Nine

[Home](https://daviey52.github.io/reading-notes/)

## Reading Notes

## Chapter 15: "Layout" (pp.358-402)

* Block level boxes start on a new line and act as the main building blocks of any layouts, while inline boxes flow between surrounding text

* if one block-level element sits inside another block-level element then the outer box is known as the containing or parent element

* CSS has the following position schemes that allow user to control the layout of a page: Normal flow , relative positioning and absolute positioning. User can specify the desired positioning using positioning property in CSS. Also float element can be used to achieve similar results.

* In a normal flow, block elements appear on a new line causing each element items to appear lower down the page than the previous one.

* Relative positioning , moves an element from the postionin it would be in a normal flow, shifting it to the top , right , bottom or left of where it would have been placed.

* Absolute positioning , move the element in relation to its containing element.

* Fixed Positioning , this is a form of absolute positining that positions the element in relation to the brower window as oppede to the containing element.

* Floating element allows the user ti take an element out of normal flow ad position it to the far left or right of a containing box. The clear property allows the user to say that no element should touch the left or right sides of a box

* when moving an element from normal flow, boxes can overlap hence the need to use the Z-index property to control which box appears on top.

* Many web pages use multiple columns in their designs. This can be achieved using a div element to represent each column

* different visitors to a website will have iffernet sized screens that show different amounts of informations. Meaning their is a need to be able to work a range of different sized screens.

* Since screen sizes and display resolution vary so much, web designer try to create web pages of around 960-1000 pixels wide.

* compostion of any visual art is the placement or arrangement of visual elements - how they are organised in a page. Many designeres use a grid structure to help them position items on a page, the same is true for web designeres.

* CSS framework are designed to help in providing the code for common task such as layout grid , styling forms , creating printer-friendly versions of pages and so on.

* Some webpage authors split up their CSS style rules into separate style sheet. There are two ways to add multiple style sheets to a page

1. Your HTML page can link o one style sheet and stylesheet can use the @import rule to import other style sheets
2. in the HTML page you can use a speparate link element for each style sheet.
