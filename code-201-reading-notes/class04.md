# Links

**Links are the defining feature of the web because they allow you to move from one web page to another — enabling the very idea of browsing or surfing.**

- Writing Links

**Links are created using the <a> element. Users can click on anything between the opening <a> tag and the closing </a> tag. You specify which page you want to link to using the href attribute.**

**Example:**

> `<a href="link">link name</a>`

- Linking to Other Sites

**Links are created using the <a> element which has an attribute called href. The value of the href attribute is the page that you want people to go to when they click on the link.**

**Example:**

> `<a href="http://www.empireonline.com">Empire</a>`

- Linking to Other Pages on the Same Site

**When you are linking to other pages within the same site, you do not need to specify the domain name in the URL. You can use a shorthand known as a relative URL.**

**Example:**

> `<a href="index.html">Home</a>`

- Email Links

`mailto:` 

**To create a link that starts up the user's email program and addresses an email to a specified email address, you use the <a> element. However, this time the value of the href attribute starts with mailto: and is followed by the email address you want the email to be sent to.**

**Example:**

> `<a href="mailto:jon@example.org">Email Jon</a>`

- Opening Links in a New Window

 `target`

**Example:**

> `<a href="http://www.imdb.com" target="_blank"> Internet Movie Database</a>`

***

## Summary

* Links are created using the <a> element.
* The <a> element uses the href attribute to indicate the page you are linking to.
* If you are linking to a page within your own site, it is best to use relative links rather than qualified URLs.
* You can create links to open email programs with an email address in the "to" field.
* You can use the id attribute to target elements within a page that can be linked to.


***

# Layout

## HTML Layout Elements

**HTML has several semantic elements that define the different parts of a web page:**

`<header>` - Defines a header for a document or a section.

`<nav>` - Defines a set of navigation links.

`<section>` - Defines a section in a document.

`<article>` - Defines an independent, self-contained content.

`<aside>` - Defines content aside from the content (like a sidebar).

`<footer>` - Defines a footer for a document or a section.

`<details>` - Defines additional details that the user can open and close on demand.

`<summary>` - Defines a heading for the `<details>` element.


## HTML Layout Techniques

**There are four different techniques to create multicolumn layouts. Each technique has its pros and cons:**

- CSS framework
- CSS float property:
**It is common to do entire web layouts using the CSS float property. Float is easy to learn - you just need to remember how the float and clear properties work. Disadvantages: Floating elements are tied to the document flow, which may harm the flexibility. Learn more about float in our CSS Float and Clear chapter.**

- CSS flexbox:
**Use of flexbox ensures that elements behave predictably when the page layout must accommodate different screen sizes and different display devices.**
- CSS grid:
**The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.**


# CSS Website Layout

- Website Layout

**A website is often divided into headers, menus, content and a footer:**

![Website layout](https://media.geeksforgeeks.org/wp-content/uploads/website_layout-300x268.png)


- Header

**A header is usually located at the top of the website (or right below a top navigation menu). It often contains a logo or the website name:**

![Header](https://lh3.googleusercontent.com/proxy/K9xTbafq5jXqWILyG0bhxMGeRAebGDKnAaoOF84IbR-Ew5GyL0xN8urqm6j6rmnOhIZP9TV6XMnwZHi-ex9d1lkb-v7vCxK0wHErE56QDcZYhnw)


- Navigation Bar

**A navigation bar contains a list of links to help visitors navigating through your website:**

![Navigation Bar](https://i.pinimg.com/originals/3b/11/a9/3b11a9900246da77cc77d89ffc635fb9.png)

- Content

**The layout in this section, often depends on the target users. The most common layout is one (or combining them) of the following:**

1. column (often used for mobile browsers)
2. column (often used for tablets and laptops)
3. column layout (only used for desktops)


![Content](https://html.com/wp-content/uploads/columns.jpg)


- Footer

**The footer is placed at the bottom of your page. It often contains information like copyright and contact info:**


![Footer](https://i.pinimg.com/originals/53/2b/6d/532b6d94bb901da7b0f9e44d68fd18a9.png)

***

# WHAT IS A FUNCTION? 

**Functions let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).**


- Declaring function and calling


![Declaring function](https://miro.medium.com/max/620/1*leb81T_gEjgGIleEykT1Dg.png)







