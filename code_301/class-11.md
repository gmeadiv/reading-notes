# Mongo and Mongoose

## SQL v. NoSQL
- What kind of data is a good fit for an SQL database? Give a real world example.
  - Heavy duty transactional applications (eBay?)
- What kind of data is a good fit a NoSQL database? Give a real world example.
- Which type of database is best for hierarchical data storage?
  - NoSQL
- Which type of database is best for scalability?
  - Both sound like they're scalable: SQL vertically by increasing processing and memory power of the server; NoSQL by adding more servers
  - NoSQL is better because vertical scaling is limited by computing power, where horizontal scaling can be indefinite.

### Video
- What does SQL stand for? \
  - Structured Query Language
- What is a realational database?
  - multiple table whose data is related to each other in some way
- What type of structure does a relational database work with?
- What is a ‘schema’?
  - the fields which all records in a table must adhere to
- What is a NoSQL database?
  - Not a Structured Language
- How does it work?
- What is inside of a Mongo database?
  - collections
- Which is more flexible - SQL or MongoDB? and why.
  - It doesn't require data to fit into a schema
- What is the disadvantage of a NoSQL database?
  - Because it doesn't have relations, it can duplicate data of lots of write request are made across multiple collections