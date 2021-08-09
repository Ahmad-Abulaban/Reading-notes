# Layout

+ position: relative

**Relative positioning moves an element in relation to where it would have been in normal flow.**

**Example:**

`h2 {`
>  `position: relative;`

`}`

***

+ position: absolute

**When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page.**


**Example:**

`h2 {`
>  `position: absolute;`
  
`}`

***

+ position: fixed

**fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed.**


**Example:**

`h2 {`
>  `position: fixed;`
  
`}`

***

+ float:

**The float property allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.**

`img {`
>  `float: right;`

`}`

***

+ clear

**The clear property allows you to say that no element (within the same containing element) should touch the left or right-hand sides of a box.**

`p.clear {`
>  `clear: left;`

`}`

***

# Summary:

- <div> elements are often used as containing elements to group together sections of a page.
- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.