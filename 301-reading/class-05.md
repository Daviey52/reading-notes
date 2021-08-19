# Class Five

[Home](https://daviey52.github.io/reading-notes/)

1. How would you break a mock into a component hierarchy?
 Drawing boxes around every component and giving them appropriate name
2. What is the single responsibility principle and how does it apply to components?
It states that a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents

3. What does it mean to build a ‘static’ version of your application?
This is a version that that takes a data model and renders the UI but has no interactivity
4. Once you have a static application, what do you need to add?
Add the minimal set of mutable state that the app needs
5. What are the three questions you can ask to determine if something is state?
• Is it passed in from a parent through props?
• Does it remain unchanged over time?
• Can you compute it based on any other state?
6. How can you identify where state needs to live
• Identify every component that renders something based on that state
• Find a common owner component
• Either the common owner or another component higher up in the hierarchy should own the state
• If you can’t find a component where it make sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component

Reference <https://reactjs.org/docs/thinking-in-react.html>
