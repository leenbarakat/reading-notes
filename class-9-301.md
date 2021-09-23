# Functional Programming Concepts 

## What is functional programming?

 Is a programming paradigm where programs are constructed by applying and composing functions.

![m](https://www.xenonstack.com/hubfs/xenonstack-functional-programming.png)

## What is a pure function and how do we know if something is a pure function?

 The function always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program's execution. It must only depend on its input arguments.

 **A function must pass two tests to be considered “pure”:**

Same inputs always return same outputs.

No side-effects.

## What are the benefits of a pure function?

One of the major benefits of using pure functions is **they are immediately testable**. They will always produce the same result if you pass in the same arguments. They also makes maintaining and refactoring code much easier.

- Pure functions encourage safe ways of programming

- Pure functions are more composable or modular

- Pure functions are easy to test and refactor

- Pure functions are memoizable

- Pure functions can be lazy

## What is immutability?

In object-oriented and functional programming, an immutable object is an object whose state cannot be modified after it is created. This is in contrast to a mutable object, which can be modified after it is created.

## What is Referential transparency?

Referential transparency, a term commonly used in functional programming, means that given a function and an input value, you will always receive the same output. That is to say there is no external state used in the function.

# Modules and require()

## What is a module?

The Module pattern is used to **mimic the concept of classes** (since JavaScript doesn't natively support classes) so that we can store both public and private methods and variables inside a single object — similar to how classes are used in other programming languages like Java or Python.

## What does the word ‘require’ do?

The require() method is used **to load and cache JavaScript modules**. So, if you want to load a local, relative JavaScript module into a Node. js application, you can simply use the require() method.

## How do we bring another module into the file the we are working in?

- To import our own Node JS module. var arthmetic = require("arthmetic");

- To import existing Node JS Module. Import Node JS “express” module; var arthmetic = require("express"); Import Node JS “mongoose” module; var mongoose = require("mongoose");

## What do we have to do to make a module available?

The first thing you do to get access to module features **is export them.** This is done using the export statement. You can export functions, var , let , const , and — as we'll see later — classes. They need to be top-level items; you can't use export inside a function, for example.
