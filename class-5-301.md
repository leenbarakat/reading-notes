# React 

## Thinking in react

### How would you break a mock into a component heirarchy?

In arrange to break a mock into a component heirarchy, you would like to to begin with know what must be a component what should a portion of a component. To do merely have to be think of making components like you think of making functions, you wish to utilize the single reponsibility principle.

### What is the single responsibility principle and how does it apply to components?

Each component must be responsibile of one thing only 

### What does it mean to build a ‘static’ version of your application?

it means  building a version of your app that only renders your data using props

### Once you have a static application, what do you need to add?

adding interactivity but before that we should  identify the minimal set of mutable state that the app needs.

### What are the three questions you can ask to determine if something is state?

1- Is it passed in from a parent via props

2- Does it remain unchanged over time

3- Can you compute it based on any other state or props in your component

### How can you identify where state needs to live?

- Identify every component that renders something based on that state.

- Find a common owner component (a single component above all the components that need the state in the hierarchy).

- Either the common owner or another component higher up in the hierarchy should own the state.

- If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

# Higher-Order Functions

## What is a “higher-order function”?

is a function that accepts functions as parameters and/or returns a function.

### Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

In line 2 the function is returning an arrow function that compares the arrow function passed variable 'm' to the main function passed variable 'n'.

### Explain how either map or reduce operates, with regards to higher-order functions.

The map method transforms an array by applying a function to all of its elements and building a new array from the returned values. The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.

with reduce operates we take for the parameters the array , combining function and starting value. the standard array method reduce, which corresponds this function, has a convenience that if our array contains at least one element we are allowed to leave off start argument the method will take the first element of the array as its start value and start reducing at the second element.


