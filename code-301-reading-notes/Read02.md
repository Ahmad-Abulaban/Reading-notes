# State

***

## Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?

**It happens first render and then componentDidMount.**

***

## What is the very first thing to happen in the lifecycle of React?

**The thing that happens first in a lifecycle is Constructor().**

***

## Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates?

* constructor
* render
* React Updates
* componentDidMount
* componentWillUnmount

***

## What does componentDidMount do?

**This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions.**

***

![React Lifecycle Events
](https://miro.medium.com/max/2000/0*0saPKFiTUk6W3FYp)

# Props

## What types of things can you pass in the props?

**In React, we may send values from a parent component to a child component via props. Strings, functions, objects, and other data types can all be used as values.**

***

## What is the big difference between props and state?

**Props are external and controlled by whatever renders the component, whereas state is internal and controlled by the component itself.**

***

## When do we re-render our application?

**whenever there is a change in their state or props.**

![React Lifecycle Events
](https://lh3.googleusercontent.com/proxy/MAgGLSE5CTCtYFUGoZq46a42dZ_i5Z7QAJlOSivHNF0012JOsWg-rED5y_7odTwAV4JPLEgrIaKeSb-2EWifIRW_-0B7QU1TxKMHAZZXx_pwZVxhWiSCtfIqkQ9R)