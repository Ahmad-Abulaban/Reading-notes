# REST

## Who is Roy Fielding?

**Roy T. Fielding, Senior Principal Scientist at Adobe, is known for his pioneering work on the World Wide Web, open source, and software architecture. He wrote the standards for HTTP/1. x and URI, has been a contributor to many other Web technologies, and defined the REST architectural style.**

***

## Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

**Because they weren't designed to be used like that. When Fielding and his colleagues started building the web, being able to talk to any machine anywhere in the world was a primary concern. But most of the techniques developers later used to get computers to talk to each other didn't have those requirements. You just needed to talk to a small group of machines.**

***

## What is the HTTP protocol that Fielding and his friends created?

**`HTTP protocol`**

* Is all about applying verbs to nouns. For instance, when you go to a web page, the browser does an HTTP GET on the URL you typed in and back comes a web page.

* Web pages usually have images, right? Those are separate resources. The web page just specifies the URLs to the images and the browser goes and does more GETs using the HTTP protocol on them until all the resources are obtained and the web page is displayed. But the important thing here is that very different kinds of nouns can be treated the same. Whether the noun is an image, text, video, an mp3, a slideshow, whatever. I can GET all of those things the same way given a URL.

***

## What does a GET do?

**`**GET is used to retrieve information from each other.`**

***

## What does a POST do?

**`If one system needs to add something to another system`**

***

## What does PUT do?

**`If a system wants to replace something in another system`**

***

## What does PATCH do?

**`use PATCH to do a partial update`**
