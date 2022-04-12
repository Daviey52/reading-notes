# Class 39

## React 3

[Home](https://daviey52.github.io/reading-notes/)

React 3
Next.JS includes some of the following useful features:

1. An intuitive page-based routing system (with support for dynamic routes)
2. Pre-rendering, both static generation (SSG) and server-side rendering (SSR) are supported on a per-page basis
3. Automatic code splitting for faster page loads
4. Client-side routing with optimized prefetching
5. Built-in CSS and Sass support, and support for any CSS-in-JS library
6. Development environment with Fast Refresh support
7. API routes to build API endpoints with Serverless Functions
8. Fully extendable

The Next.js development server has Fast Refresh enabled. When you make changes to files, Next.js automatically applies the changes in the browser almost instantly. No refresh needed! This will help you iterate on your app quickly. Next.js does code splitting automatically, so each page only loads what’s necessary for that page. That means when the homepage is rendered, the code for other pages is not served initially.
Images are lazy loaded by default. That means your page speed isn't penalized for images outside the viewport. Images load as they are scrolled into viewport.

### React context

React context allows us to pass down and use (consume) data in whatever component we need in our React app without using props. React context is great when you are passing data that can be used in any component in your application.These types of data include:

1. Theme data (like dark or light mode)
2. User data (the currently authenticated user)
3. Location-specific data (like user language or locale)

React context helps us avoid the problem of props drilling. Props drilling is a term to describe when you pass props down multiple levels to a nested component, through components that don't need it. Context is an API that is built into React, starting from React version 16. This means that we can create and use context directly by importing React in any React project.
