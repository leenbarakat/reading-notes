# Lists and Keys

## What does .map() return?

To take an array of numbers and double their values. We assign the new array returned by map() to the variable doubled and log it

## If I want to loop through an array and display each value in JSX, how do I do that in React?

Showing a list of items is crucial in every single application we'll build. Using JSX we can show lists using JavaScript's built-in Array.map() method.

The .map() is often used to take one piece of data and convert it to another. In our scenarios, we are taking data and converting it to a piece of our view.

##  Each list item needs a unique ____.

Each list item should have a unique "key" prop.

## What is the purpose of a key?

Is used React to identify changed, added or remobed items.

# The spread operator

## What is the spread operator?

![k](https://miro.medium.com/max/1000/1*oB0L8ezFrNnU9aR55BrEng.png)

allows an iterable to expand in places where 0+ arguments are expected. It is mostly used in the variable array where there is more than 1 values are expected. It allows us the privilege to obtain a list of parameters from an array.

Spread syntax can be used when all elements from an object or array need to be included in a list of some kind.

## List 4 things that the spread operator can do.

1- Copying an array.

2- Using Math functions.

3- Adding an item to a list.

4- Adding to state in React.

## Spread operator to combine two arrays.

const objectOne = {hello: “🤪”}

const objectTwo = {world: “🐻”}

const objectThree = {…objectOne, …objectTwo, laugh: “😂”}

console.log(objectThree) // Object { hello: “🤪”, world: “🐻”, laugh: “😂” }

const objectFour = {…objectOne, …objectTwo, laugh: () => {console.log(“😂”.repeat(5))}}

objectFour.laugh() // 😂😂😂😂😂

## Spread operator to add a new item to an array

const names = ['nathan', 'ahmad', 'john'];
const moreNames = ['mike', ...names];
console.log(moreNames);

## Spread operator to combine two objects into one

const objectOne = {p1: 'Hello Im object 1'};
const objectTwo = {p2: 'Hellow Im object 2'};
const objectThree = {...objectOne, ...objectTwo, p3: 'Hellow Im object 3'};
console.log(objectThree);
const objectFour = {...objectOne, ...objectTwo, p4: () => {console.log("Hellow Im object 4".repeat(5))}};
objectFour.p4();

# Passing Functions Between Components

1- In the video, what is the first step that the developer does to pass functions between components?

He used the map() function to loop through the arrays 

2- In your own words, what does the increment function do?

The increment operator (++) increments its operand by 1; that is, it adds 1 to the existing value. There's a corresponding decrement operator (--) that decrements a variable's value by 1. That is, it subtracts 1 from the value. JavaScript provides these operators since incrementing and decrementing by 1 are such commonplace operations.

3- How can you pass a method from a parent component into a child component?

By using props 

4- How does the child component invoke a method that was passed to it from a parent component?

using this.props.propsname

