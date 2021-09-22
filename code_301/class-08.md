# APIs

## API Design Best Practices
1. What does REST stand for?
  - representational state transfer
2. REST APIs are designed around a what?
  - resources (any kind of object, data, or service that can be accessed by the client)
3. What is an identifer of a resource? Give an example.
  - a website URL
4. What are the most common HTTP verbs?
  - GET, POST, PUT, PATCH, and DELETE.
5. What should the URIs be based on?
  - nouns (the resource) not verbs (operations on the resource)
6. Give an example of a good URI.
  - school.edu/students/account/billing
7. What does it mean to have a ‘chatty’ web API?
  - an api that exposes a large number of small resources
8. Is this a good or a bad thing?
  - bad thing bc it requires the web server to make many requests when only one would be better
9. What status code does a successful GET request return?
  - 200
10. What status code does an unsuccessful GET request return?
  - 404
11. What status code does a successful POST request return?
  - 201
12. What status code does a successful DELETE request return?
  - 204