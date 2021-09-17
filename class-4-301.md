# React docs - forms 

## What is a ‘Controlled Component’?

is a component that renders form elements and controls them by keeping the form data in the component's state. In a controlled component, the form element's data is handled by the React component (not DOM) and kept in the component's state.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

We should wait to store the users responses from the form, because the user might wants to change something in the inputs. For me I think it is better to wait until the user submit all responses to store all the data at once.

## How do we target what the user is entering if we have an event handler on an input field?

by using the value attribute for the form or the input field.

# The Conditional (Ternary) Operator

## Why would we use a ternary operator?

A ternary operator allows you to assign one value to the variable if the condition is true, and another value if the condition is false.

## Rewrite the following statement using a ternary statement

 if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

  In ternary statement:

  ***console.log(x===y ? 'true' : 'false');***