# HTML links 

Links are found in nearly all web pages. Links allow users to click their way from page to page.

## HTML Links - Hyperlinks
HTML links are hyperlinks.

You can click on a link and jump to another document.

When you move the mouse over a link, the mouse arrow will turn into a little hand.

**HTML links syntax**

![img](https://www.computerhope.com/jargon/h/html-tag.gif)

By default, links will appear as follows in all browsers:

- An unvisited link is underlined and blue

- A visited link is underlined and purple

- An active link is underlined and red

To read more about links visit [HTML links](https://www.w3schools.com/html/html_links.asp)

# CSS layouts

Website Layout
A website is often divided into headers, menus, content and a footer:

![img](https://cdn.codecoda.com/themes/user/site/default/asset/img/blog/CSS-layout-4.png)

## Header

A header is usually located at the top of the website (or right below a top navigation menu). It often contains a logo or the website name

## Navigation Bar

A navigation bar contains a list of links to help visitors navigating through your website

## Content

The layout in this section, often depends on the target users. The most common layout is one (or combining them) of the following:

- **1-column** (often used for mobile browsers)

- **2-column** (often used for tablets and laptops)

- **3-column** layout (only used for desktops)

## Unequal Columns

The main content is the biggest and the most important part of your site.

It is common with unequal column widths, so that most of the space is reserved for the main content. The side content (if any) is often used as an alternative navigation or to specify information relevant to the main content. Change the widths as you like, only remember that it should add up to 100% in total.

## Footer

The footer is placed at the bottom of your page. It often contains information like copyright and contact info

# Functions in JavaScript

Functions are one of the basic building blocks in JavaScript. A work in JavaScript is comparable to a procedure—a set of explanations that performs a assignment or calculates a esteem, but for a method to qualify as a work, it ought to take a few input and return an yield where there's a few self-evident relationship between the input and the yield. To use a work, you must define it somewhere within the scope from which you would like to call it.

## Function declarations 
A function definition (also called a function declaration, or function statement) consists of the function keyword, followed by:

The name of the function.
A list of parameters to the function, enclosed in parentheses and separated by commas.
The JavaScript statements that define the function, enclosed in curly brackets, {...}.

## Function expressions
While the function declaration above is syntactically a statement, functions can also be created by a function expression.

Such a function can be anonymous; it does not have to have a name. 

## Calling functions 
Defining a function does not execute it. Defining it names the function and specifies what to do when the function is called.

Calling the function actually performs the specified actions with the indicated parameters. 

## Function scope 
Variables defined inside a function cannot be accessed from anywhere outside the function, because the variable is defined only in the scope of the function. However, a function can access all variables and functions defined inside the scope in which it is defined.

In other words, a function defined in the global scope can access all variables defined in the global scope. A function defined inside another function can also access all variables defined in its parent function, and any other variables to which the parent function has access.

You can read more about functions by visiting [Functions in JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

# Operators 

**Types of operators in JavaScript**

1. Assignment operators

2. Comparison operators

3. Arithmetic operators

4. Bitwise operators

5. Logical operators

6. String operators

7. Conditional (ternary) operator

8. Comma operator

9. Unary operators

10. Relational operators

1. ** Assignment operators **

An assignment operator assigns a value to its left operand based on the value of its right operand. The simple assignment operator is equal (=), which assigns the value of its right operand to its left operand. That is, x = y assigns the value of y to x.

2. ** Comparison operators**

A comparison operator compares its operands and returns a logical value based on whether the comparison is true. The operands can be numerical, string, logical, or object values. Strings are compared based on standard lexicographical ordering, using Unicode values. In most cases, if the two operands are not of the same type, JavaScript attempts to convert them to an appropriate type for the comparison. This behavior generally results in comparing the operands numerically. The sole exceptions to type conversion within comparisons involve the === and !== operators, which perform strict equality and inequality comparisons. These operators do not attempt to convert the operands to compatible types before checking equality. 


3. **Arithmetic operators**

An arithmetic operator takes numerical values (either literals or variables) as their operands and returns a single numerical value. The standard arithmetic operators are addition (+), subtraction (-), multiplication (*), and division (/). These operators work as they do in most other programming languages when used with floating point numbers (in particular, note that division by zero produces Infinity).

4. **Bitwise operators**

A bitwise operator treats their operands as a set of 32 bits (zeros and ones), rather than as decimal, hexadecimal, or octal numbers. For example, the decimal number nine has a binary representation of 1001. Bitwise operators perform their operations on such binary representations, but they return standard JavaScript numerical values.


5. **Logical operators**

Logical operators are typically used with Boolean (logical) values; when they are, they return a Boolean value. However, the && and || operators actually return the value of one of the specified operands, so if these operators are used with non-Boolean values, they may return a non-Boolean value. The logical operators are described in the following table.

6. **String operators**

In addition to the comparison operators, which can be used on string values, the concatenation operator (+) concatenates two string values together, returning another string that is the union of the two operand strings.


7. **Conditional (ternary) operator**

The conditional operator is the only JavaScript operator that takes three operands. The operator can have one of two values based on a condition.

8. **Comma operator**

The comma operator (,) evaluates both of its operands and returns the value of the last operand. This operator is primarily used inside a for loop, to allow multiple variables to be updated each time through the loop. It is regarded bad style to use it elsewhere, when it is not necessary. Often two separate statements can and should be used instead.

9. **Unary operators**

A unary operation is an operation with only one operand.


10. **Relational operators**

A relational operator compares its operands and returns a Boolean value based on whether the comparison is true.

***To read more about the expressions and operators in details with examples visit [operators CSS](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)***
