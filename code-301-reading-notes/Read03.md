# Passing Functions as Props

## What does .map() return?

**The map() method calls a callback function on every element of an array and returns a new array that contains the results.**

***

## Each list item needs a unique _Key__.

***

## What is the purpose of a key?

**Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.**

***

## What is the spread operator?

**The Spread operator expands an iterable, such as an object, string, or array, into its elements, whereas the Rest operator reduces a collection of elements into one array.**

***

## List 4 things that the spread operator can do.

* Adding to state in React.
* Combining objects.
* Adding an item to a list.
* Converting NodeList to an array.

***

## Give an example of using the spread operator to combine two arrays?

**Example:**

> `let fruits = ["apples", "bananas"];`

> `let vegetables = ["corn", "carrots"];`

> `let produce = [...fruits, ...vegetables];`

***

## Give an example of using the spread operator to add a new item to an array?

**Example:**

> `const odd = [1,3,5];`

> `const combined = [2,4,6, ...odd];`

***

## what is the first step that the developer does to pass functions between components?

**determines the next node at the same level.**

![Passing Functions as Props](https://i.ytimg.com/vi/szmS_M-BMls/mqdefault.jpg)

