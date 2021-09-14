# React and Forms

## What is a ‘Controlled Component’?

**A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state. In a controlled component, the form element's data is handled by the React component (not DOM) and kept in the component's state.**

***

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why?

**Form components like input, textarea, and select in HTML generally keep their own state and change it based on user input. In React, mutable state is generally stored in component state and only changed using setState ().**

***

## How do we target what the user is entering if we have an event handler on an input field?

* Since the value attribute is set on our form element, the displayed value will always be this.state.value, making the React state the source of truth. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.

* With a controlled component, the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

***

## Why would we use a ternary operator?

* A ternary operator allows you to assign one value to the variable if the condition is true, and another value if the condition is false.

* A ternary operator makes the assignment of a value to a variable easier to see, because it's contained on a single line instead of an if else block.

***

## Rewrite the following statement using a ternary statement:

  `if(x===y){`

> `console.log(true);`

  `} else {`

> `console.log(false);`

  `}`

**Solution:**

`x===y ? console.log(true) : console.log(false)`