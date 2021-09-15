# Putting it all together

## How would you break a mock into a component heirarchy?

**Draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components.**

***

## What is the single responsibility principle and how does it apply to components?

* a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

* That is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

***

## What does it mean to build a ‘static’ version of your application?

**all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies.**

***

## What are the three questions you can ask to determine if something is state?

* Is it passed in from a parent via props?
* Does it remain unchanged over time?
* Can you compute it based on any other state or props in your component?

***

## How can you identify where state needs to live?

* Identify every component that renders something based on that state.
* Find a common owner component (a single component above all the components that need the state in the hierarchy).
* Either the common owner or another component higher up in the hierarchy should own the state.
* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

