# Relational and Non-relational Databases Study

Read the following articles thoroughly. Practice active reading by taking notes.

-   [NoSQL Databases Explained | MongoDB](https://www.mongodb.com/nosql-explained)
-   [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/) (click
    through to at least one detailed example)
-   [Why You Sould Never Use MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/)

As you read, pay special attention to addressing the following:

-   Identify use cases where relational or non-relational databases are
    appropriate.
-   List three strengths of relational databases.
-   List three strengths of non-relational databases.

After you've finished your study, summarize your notes to the following section
and open a pull request.

Be prepared to share your notes with others before the discussion. Everyone
should have something to contribute.

## Summary

# NoSQL Intro
- massive amounts of data, all different types
  - need to scale massively and quickly
- databases include:
  - document databases
  - graph stores
  - key-value stores
  - wide-column stores

- NoSQL databases more scalable with better performance (ex. MongoDB, Cassandra)
  - can insert data without pre-defining schema
    - dev is faster, code integration more reliable, less admin time needed
  - can scale horizontally by adding servers
    - auto-sharding: natively spread data across # of servers
      - uses cloud computing
    - servers can automaticly replicate database
      - many self-healing; can also distribute database across regions
      - NoSQL databases dont need any add-ons for replication

# MongoDB Intro
- operational intelligence
- product data management
- content management

# Why You Should Never Use MongoDB
- MongoDB is a document-oriented database. Instead of storing your data in tables made out of individual rows, like a relational database does, it stores your data in collections made out of individual documents. In MongoDB, a document is a big JSON blob with no particular format or schema.

- When MongoDB is all you have, it’s a cache with no backing store behind it. It will become inconsistent. Not eventually consistent — just plain, flat-out inconsistent, for all time. At that point, you have no options. Not even a nuclear one. You have no way to regenerate the data in a consistent state.

- Remember that TV show application? It was the perfect use case for MongoDB. Each show was one document, perfectly self-contained. No references to anything, no duplication, and no way for the data to become inconsistent.

- MongoDB’s ideal use case is even narrower than our television data. The only thing it’s good at is storing arbitrary pieces of JSON. “Arbitrary,” in this context, means that you don’t care at all what’s inside that JSON. You don’t even look. There is no schema, not even an implicit schema, as there was in our TV show data. Each document is just a blob whose interior you make absolutely no assumptions about.
