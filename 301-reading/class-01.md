# Class One

[Home](https://daviey52.github.io/reading-notes/)

## Component Based Architecture

### What is a component

* A component is a software object, intended to interact with other components, encapsulating certain functionality or a set of functionalities. It has an obviously defined interface and conforms to a recommended behavior common to all components within an architecture.

* A component is a modular, portable, replaceable, and reusable set of well-defined functionalities that encapsulates its implementation and exporting it as a higher-level interface.

### What are the characteristics of a component

1. Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.
2. Replaceable − Components may be freely substituted with other similar components.
3. Encapsulated − A  component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.
4. Independent − Components are designed to have minimal dependencies on other components.

### What are the advantages of using component based architecture

1. Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.
2. Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.
3. Ease of development − Components implement well-known interfaces to provide defined functionality, allowing development without impacting other parts of the system.
4. Reusable − The use of reusable components means that they can be used to spread the development and maintenance cost across several applications or systems.

## What is props short for

* “Props” is a special keyword in React, which stands for properties and is being used for passing data from one component to another.

* React is a component-based library which divides the UI into little reusable pieces. In some cases, those components need to communicate (send data to each other) and the way to pass data between components is by using props.

### How are props used in React?

1.Define an attribute and its value data
2.Passed to a child component by use of props
3. Rendered the props data.

### What is the flow of props?

* props can only be passed to components in one-way(parent to child)
