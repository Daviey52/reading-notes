# Class 37

## React 1

[Home](https://daviey52.github.io/reading-notes/)

JSX produces React “elements”. react embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display. Instead of artificially separating technologies by putting markup and logic in separate files, react separates concerns with loosely coupled units called “components” that contain both. After compilation, JSX expressions become regular JavaScript function calls and evaluate to JavaScript objects.

By default, React DOM escapes any values embedded in JSX before rendering them. Thus, it ensures that you can never inject anything that’s not explicitly written in your application. Everything is converted to a string before being rendered. This helps prevent XSS (cross-site-scripting) attacks.

Unlike browser DOM elements, React elements are plain objects, and are cheap to create. React DOM takes care of updating the DOM to match the React elements. Applications built with just React usually have a single root DOM node. If you are integrating React into an existing app, you may have as many isolated root DOM nodes as you like. To render a React element, first pass the DOM element to ReactDOM.createRoot(), then pass the React element to root.render():

Components can refer to other components in their output. This lets us use the same component abstraction for any level of detail. A button, a form, a dialog, a screen: in React apps, all those are commonly expressed as components.

### Important benefits of Tailwind CSS

• No classNames required
• CSS is reusable, now new CSS is needed
• Making changes feels safer
