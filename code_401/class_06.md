# Authentication

1. What is middleware?

- a function which is executed during the request pipeline (between the request and the response)

  - next must be called in order to move on to another function

  - error: an optional parameter which triggers error-handling middleware when passed into the next function

Understand middleware and you can make express do anything. Anything. Any. Thing.

2. Sequalize Data Modeling

- define a model for sequelize
- connection string
- database to which our models connect

- Unit test: tests one single thing (a unit)
- Integration test: tests many things and how they integrate

## Authentication lecture notes

- who is the user?
  - can the user tell me who they are?
  - can i validate that?
- this is different from Authorization (i.e. "is the user allowed to do something?")

### encoding and encryption

Authentication HTTP requests with headers

- credentials are encoded: formalizing and standardizing an input in order for the machine to read passwords properly
- encryption hides this information by making it really hard for a computer to read it
- encode => decode (briefly) => encrypt
- NEVER LOG UNENCRYPTED STUFF

## Reading Notes

1. Explain what a “Singleton” is (in Computer Science terms)

- a design pattern which restricts the instantiation of a class to a single instance

2. Explain how the Singleton pattern can be used with Node modules, specifically with classes

- within the class's constructor function, you'd check to see if an instance of the class has already been made
- if an instance exists, it can either be returned or be replaced with a new one
- if no instance exists, one is created

3. If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?

- REST

### Document the following Vocabulary Terms

- Router Middleware: manages incoming HTTP requests

- Dynamic Module Loading: allows the computer to load a library, retreive data and execute functions from within the library, then unloads the library from memory

- Singleton Pattern: ensures there's only ever a single instance of an object

- CRUD -> REST Method Matches: POST - Create, GET - Read, PUT - Update/Replace, PATCH - Update/Modify, DELETE - Delete

- Mock Testing: helps test run more quicklier and reliablier
