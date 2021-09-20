# Problem Domain, Objects, and the DOM
## The problem domain

## object literals
- property is a variable that is part of an object
- a method is a function that is part of an object
- literal notation is the easiest and most popular way to create objects

## document object model (DOM)
- specifies how browsers should create a model of an html page and how JS can access and update the contents of a page while it is in the browser window

## const
- a way to declare a constant variable (ie a variable i don't plan on changing)
- `const bestDog = 'indiana'` as opposed to `let bestDog = 'indiana'`
- const is commonly used with arrays and objects because we can change the interior of those without changing the value of the variable
- prevents error, helps to tell a story with my code

## Objects
- JS objects are convenient and powerful ways to group data and functions
  - stores data of varying types to describe something
  - store data as properties which are represented as value pairs
  - similar to arrays but with semantic or explicit element names
  - objects use curly brackets, arrays use square brackets
  - try not to mix data types with arrays, but for objects is ok
- contextual this
  - `console.log(this.name + ' come!')` [this] = [myDog]