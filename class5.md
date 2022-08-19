# React Docs - Thinking in React
What is the single responsibility principle and how does it apply to components? A component should ideally only do one thing. If it ends up growing, it should be 
decomposed into smaller subcomponents.

What does it mean to build a ‘static’ version of your application?  Static applications and websites render in the user's browser without the need for server side 
processing.

Once you have a static application, what do you need to add? You need ti build components that reuse other components and pass data using props. 

What are the three questions you can ask to determine if something is state?
- Is it passed in from a parent via props? If so, it probably isn’t state.
- Does it remain unchanged over time? If so, it probably isn’t state.
- Can you compute it based on any other state or props in your component? If so, it isn’t state.

How can you identify where state needs to live? Identify every component that renders something based on your state. 

Higher-Order Functions

What is a “higher-order function”? A higher order function is a function that is taken as an argument.

Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing? Link to article isn't rendering. Broken link. Will 
revisit to see it link is up and running. 

Explain how either map or reduce operates, with regards to higher-order functions. `map` method creates a new array by calling a provided function on every element. 
`reduce` executes a reducer function for array element. 
