# Express REST API

## Name 3 real world use cases where you’d want to change the request with custom middleware

1. error handlers

2. print message

3. request timestamp

## True or false: The route handler is middleware?

False

## In what ways can a middleware function end the process and send data to the browser?

- next(), response.send; .status, .end

## At what point in the request lifecycle can you “inject” middleware?

Between the method and the path

## What can cause express to error with “Request headers sent twice, cannot start a second response”

- Another function tried to set a header or status code.

- You are already in the Body or Finished state.

- A callback may have accidentally been called twice.

## Document the following Vocabulary Terms

### Middleware

Functions that exist between the method and the path

### Request Object

An object that contains the data sent to the server within an HTTP request

### Response Object

An object which contains the data the server sends back after receiving a request

### Application Middleware

Called with app.use()

### Routing Middleware

Bound to an instance of express.Router()

### Test Driven Development

A programming style involving coding, testing, and design/refactoring