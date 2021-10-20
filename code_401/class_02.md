# CLASS TWO NOTES

## Lecture notes

- what is node dot js?
  - lets us run JS outside of a browser
  - i.e. a "runtime"
- what is require?
  - function which allows us to use a library (i.e. node library)
  - gives the runtime with an object to use
- what is a node module?
  - a file / group of files in Node
  - a program that is exported to be used elsewhere
- what is express used for?
  - URL pathways => HTTP Requests
  - allows for RESTful web service design
- what is a Request?
  - something sent to a server
  - in express how do we interface with this Request?
    - Get, Post, Delete, Put
- what is a Response?
  - the thing the server sends back

- what is middleware?
  - any program that runs in between two other programs
- what is middleware in the express context?
  - function that runs in between the request and the response
    - Next function passes the baton to the next program
    - Optional error parameter to handle errors

## Reading Notes

1. What’s the difference between PUT and PATCH?
  - a put request replaces the resource with a modified copy
  - a patch request is a set of instructions to modify the resource itself

2. Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
  - [Postman](https://www.postman.com/)
  - [Swagger](https://swagger.io/)
  - [Mocki](https://github.com/adalyte/mocki)

3. Compare and contrast Swagger and APIDoc.js
  - Which HTTP status codes should be sent with each type of (un)successful API call?
    - 200 codes are successful
    - 400 codes are error codes indicating the client has done something wrong
    - 500 codes are error codes indicating the server has done something wrong

4. Compare and contrast SOAP and ReST
  - Simple Object Access Protocol
    - is a protocol
  - Representational State Transfer
    - is not a protocol

### Web Server

- hosts resources for clients

### Express

- allows for RESTful web service design

### Routing

- the paths and parameters that a server should handle

### WRRC

- Web Request/Response Cycle
