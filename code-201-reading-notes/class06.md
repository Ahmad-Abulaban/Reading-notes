## Understanding The Problem Domain Is The Hardest Part Of Programming

**What is the hardest thing about writing code?**

+ Learning a new technology.
+ Naming things.
+ Testing your code.
+ Debugging.
+ Fixing bugs.
+ Making software maintainable.


***

# What is an object?

**An object, in object-oriented programming (OOP), is an abstract data type created by a developer. It can include multiple properties and methods and may even contain other objects. In most programming languages, objects are defined as classes.**


***

# Object Literal

**An object literal is a comma-separated list of name-value pairs inside of curly braces. Those values can be properties and functions. Here’s a snippet of an object literal with one property and one function.**

## Example

`var greeting = {`

>    `fullname: "Michael Jackson",`

>    `greet: (message, name) => {`

>       console.log(message + " " + name + "!!");

>    `}`

***

Summary:

+ Functions allow you to group a set of related statements together that represent a single task.
+ Functions can take parameters (informatiorJ required to do their job) and may return a value.
+ An object is a series of variables and functions that represent something from the world around you.
+ In an object, variables are known as properties of the object; functions are known as methods of the object.
+ Web browsers implement objects that represent both the browser window and the document loaded into the browser window.
+ JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.
+ Arrays and objects can be used to create complex data sets (and both can contain the other). 


***


# Document Object Model

+ DOM TREE 

**The Document Object Model (DOM) is a programming API for HTML and XML documents. It defines the logical structure of documents and the way a document is accessed and manipulated.**

**Example**

![Dom tree](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png)

***


# Summary DOM

+ The browser represents the page using a DOM tree.
+ DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
+ You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.
+ Whenever a DOM query can return more than one node, it will always return a Nadel i st.
+ From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques.
+ An element node can contain multiple text nodes and child elements that are siblings of each other.
+ In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
+ Browsers offer tools for viewing the DOM tree . 
