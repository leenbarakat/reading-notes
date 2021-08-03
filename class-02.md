
 # headings in html

headings:
h1 is used for main headings

h2 is used for subheadings
If there are further sections
under the subheadings then the
h3 element is used, and so
on..

![img](https://www.schudio.com/wp-content/uploads/2016/10/html-headings.png?x43850)

to know more about HTML features visit [HTML](https://www.w3schools.com/html/html_elements.asp)

## CSS 

Cascading Style Sheets, fondly referred to as CSS, is a simply designed language intended to simplify the process of making web pages presentable. CSS allows you to apply styles to web pages. More importantly, CSS enables you to do this independent of the HTML that makes up each web page.
CSS is easy to learn and understood, but it provides powerful control over the presentation of an HTML document.

WHY CSS? 

**CSS saves time:** You can write CSS once and reuse the same sheet in multiple HTML pages.


**Easy Maintainence:**To make a global change simply change the style, and all elements in all the webpages will be updated automatically.


**Search Engines:** CSS is considered a clean coding technique, which means search engines won’t have to struggle to “read” its content.


**Superior styles to HTML:** CSS has a much wider array of attributes than HTML, so you can give a far better look to your HTML page in comparison to HTML attributes.


**Offline Browsing:** CSS can store web applications locally with the help of an offline cache. Using this we can view offline websites.


**CSS Syntax:**
A CSS comprises style rules that are interpreted by the browser and then applied to the corresponding elements in your document.
A style rule set consists of a selector and declaration block.

CSS Selectors
CSS selectors are used to “find” (or select) HTML elements based on their element name, id, class, attribute, and more. 


The selector points to the HTML element you want to style.
The declaration block contains one or more declarations separated by semicolons.
Each declaration includes a CSS property name and a value, separated by a colon.
For Example:
–; color is property and blue is value.
–; font size is property and 12px is value.
A CSS declaration always ends with a semicolon, and declaration blocks are surrounded by curly braces.

To know more about CSS visit [CSS](https://www.geeksforgeeks.org/css-introduction/)
 
 ## JavaScript instruction 

 **Using a Variable to Store a Number**

 // Create three variables to store the information needed.
var price;
var quantity;
var total;

// Assign values to the price and quantity variables.
price = 5;
quantity = 14;
// Calculate the total by multiplying the price by quantity.
total = price * quantity;

// Get the element with an id of cost.
var el = document.getElementById('cost');
el.textContent = '$' + total;

 **Using a Variable to Store a String**

 // Create variables to hold the name and note text.
var username;
var message;

// Assign values to these variables.
username = 'Molly';
message = 'See our upcoming range';

// Get the element with an id of name.
var elName = document.getElementById('name');
// Replace the content of this element.
elName.textContent = username;

// Get the element with an id of note.
var elNote = document.getElementById('note');
// Replace the content of this element.
elNote.textContent = message;

**Using Quotes Inside a String**

// Create variables to hold the title and note text.
var title; 
var message;

// Assign values to these variables.
title = "Molly's Special Offers";
message = 'a href=\"sale.html\"25% off!</a>';

// Get the element with an id of title.
var elTitle = document.getElementById('title');
// Replace the content of this element.
elTitle.textContent = title;

// Get the element with an id of note.
var elNote = document.getElementById('note');
// Replace the content of this element.
elNote.innerHTML = message;

**Using a Variable to Store a Boolean**

// create variables and assign their values
var inStock;
var shipping;
inStock = true;
shipping = false;

// get the element that has an id of stock
var elStock = document.getElementById('stock');
// Set class name with value of inStock variable
elStock.className = inStock;

// get the element that has an id of shipping
var elShip = document.getElementById('shipping');
// Set class name with value of shipping variable
elShip.className = shipping;

To know more visit [JS intructions](http://javascriptbook.com/code/c02/)

## Decisions and loops 

**Conditional Statements**

Very often when you write code, you want to perform different actions for different decisions.

You can use conditional statements in your code to do this.

In JavaScript we have the following conditional statements:

- Use if to specify a block of code to be executed, if a specified condition is true

- Use else to specify a block of code to be executed, if the same condition is false

 
- Use else if to specify a new condition to test, if the first condition is false

- Use switch to specify many alternative blocks of code to be executed

**The if Statement**

Use the if statement to specify a block of JavaScript code to be executed if a condition is true.

**The else Statement**

Use the else statement to specify a block of code to be executed if the condition is false.

**The else if Statement**

Use the else if statement to specify a new condition if the first condition is false.

## Loops

Loops are handy, if you want to run the same code over and over again, each time with a different value.

**Different Kinds of Loops**

JavaScript supports different kinds of loops:

- for - loops through a block of code a number of times

- for/in - loops through the properties of an object

- for/of - loops through the values of an iterable object

- while - loops through a block of code while a specified condition is true

- do/while - also loops through a block of code while a specified condition is true

To know more visit [Loops](https://www.w3schools.com/js/js_loop_for.asp)
