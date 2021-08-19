# Class Three

[Home](https://daviey52.github.io/reading-notes/)

1. What does .map() return?
Returns a list
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
Through the use of curly braces {}.
3. Each list item needs a unique key
4. What is the purpose of a key?
Key help react identify which items have changed, are added, or are removed

• The Spread Operator

1. What is the spread operator?
It is the use of an ellipse of three dots (…) used to expand an iterable object into the list of arguments
2. List 4 things that the spread operator can do.
• Copy an array
• Combine objects
• Add an item to a list
• Concatenating or combining arrays
3. Give an example of using the spread operator to combine two arrays.
Code credit =medium.com
const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

4.Give an example of using the spread operator to add a new item to an array.
Code Credit:Medium.com
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]

5.Give an example of using the spread operator to combine two objects into one.
Code credit;Medium.com
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

video<https://www.youtube.com/watch?v=c05OL7XbwXU>

1. In the video, what is the first step that the developer does to pass functions between components?
  Create the function in the parent component
2. In your own words, what does the increment function do?
Maps the people array so that it can update state based on which name  that was passed. The increment function changes, the count property based on click
3. How can you pass a method from a parent component into a child component?
Passed by use of props
4. How does the child component invoke a method that was passed to it from a parent component?
By calling the passed method in the child component

Reference: <https://reactjs.org/docs/lists-and-keys.html>
          :<https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab>
