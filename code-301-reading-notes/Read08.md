# APIs

## What does REST stand for?

**Is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.**

***

## REST APIs are designed around a __`resources`__.

***

## What is an identifer of a resource? Give an example?

**A resource has an identifier, `which is a URI that uniquely identifies that resource.` For example, the URI for a particular customer order might be.**

***

## What are the most common HTTP verbs?

**The most common operations are `GET`, `POST`, `PUT`, `PATCH`, and `DELETE`.**

***

## What should the URIs be based on?

**resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).**

***

## Give an example of a good URI?

> `example.com/customers/1/orders/99/products`

***

## What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

**Reason why chatty APIs are considered poor quality is because requiring multiple network calls will slow down an application. This is because each call contains data overhead (i.e. sender information, headers, authentication) which will slow down an application as well as network latency per each request.**

***

## What status code does a successful GET request return?

**A successful GET method typically returns HTTP status code 200 (OK).**

***

## What status code does an unsuccessful GET request return?

**The method should return 404 (Not Found).**

***

## What status code does a successful POST request return?

**it returns HTTP status code 201 (Created).**

***

## What status code does a successful DELETE request return?

**HTTP status code 204 (No Content), indicating that the process has been successfully.**
