# Lists

**The are three different types About lists:**

* Ordered lists are lists where each item in the list is numbered.

**Example:**

`<ol>`

> `<li></li>`

`</ol>`

* Unordered lists are lists that begin with a bullet point.

**Example:**

`<ul>`

> `<li></li>`

`</ul>`

* Definition lists are made up of a set of terms along with the definitions for each of those terms.

**Example:**

`<dl>`

`<dt>Sashimi</dt>`

> `<dd>Sliced raw fish that is served with
 condiments such as shredded daikon radish or
 ginger root, wasabi and soy sauce</dd>`

 `</d1>`


 # Summary

+ Ordered lists use numbers.

+ Unordered lists use bullets.

+ Definition lists are used to define terminology.

+ Lists can be nested inside one another.


# Boxes

- Box Dimensions

> `width, height`

`p {`

`height: 75%;`

`width: 75%;`

`}`

***

- Limiting Width

> `min-width, max-width`

`td.description {`

`min-width: 450px;`

`max-width: 650px;`

`}`

***

- Limiting Height

> `min-height, max-height`

`p {`

`min-height: 10px;`

`max-height: 30px;`

`}`

***

# Border, Margin & Padding

- Border:
**Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.**

- Margin:
**Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.**

- Padding:
**Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.**

![Border, Margin & Padding](https://blog.hubspot.com/hs-fs/hubfs/Google%20Drive%20Integration/Update%20css%20margin%20vs%20padding-2.png?width=650&name=Update%20css%20margin%20vs%20padding-2.png)


# Summary

- CSS treats each HTML element as if it has its own box.
- You can use CSS to control the dimensions of a box.
- You can also control the borders, margin and padding for each box with CSS.
- It is possible to hide elements using the display and visibility properties.
- Block-level boxes can be made into inline boxes, and inline boxes made into block-level boxes.


# Basic Javascript and instructions

* STATEMENTS

**A script is a series of instructions that a computer can follow one-by one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.**

* COMMENTS

**You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.**

`/* code */` `Or` `// code`

## WHAT IS A VARIABLE?

**A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.**

![VARIABLE](https://media.geeksforgeeks.org/wp-content/uploads/20191110223008/java-declare.jpeg)

* ARRAYS

**An array is a special type of variable. It doesn't just store one value; it stores a list of values.**


# Summary

- A script is made up of a series of statements. Each statement is like a step in a recipe.

- Scripts contain very precise instructions. For example, you might specify that a value must be remembered before creating a calculation using that value.

- Variables are used to temporarily store pieces of information used in the script.

- Arrays are special types of variables that store more than one piece of related information.

- JavaScript distinguishes between numbers (0-9), strings (text), and Boolean values (true or false).

- Expressions evaluate into a single value.

- Expressions rely on operators to calculate a value. 


# Decisions & Loops

## SWITCH STATEMENTS

**Example:**

`switch (level) {`

> `case 'One ':`

`Code`

`break;`

> `case 'Two':`

`code`

`break;`

> `case ' Three' :`

`code`

`break ;`

> `default :`

`code`

`break; `

`}`

## Loops

**Example:**

`for (i = O; i < arraylength; i++) {` 

> `Code`

`}`

# Summary

- switch statements allow you to compare a value against possible outcomes (and also provides a default option if none match).

- Data types can be coerced from one type to another.

- All values evaluate to either truthy or falsy.

- There are three types of loop: for, while, and do ... while. Each repeats a set of statements. 
