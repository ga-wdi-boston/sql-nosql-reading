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

<!-- your notes here -->

Relational databases were not designed to cope with the scale and agility
challenges that face modern applications, nor were they built to take advantage
of the commodity storage and processing power available today.

NoSQL Database Types

- Document databases pair each key with a complex data structure known as a document.
  Documents can contain many different key-value pairs, or key-array pairs, or
  even nested documents.
- Graph stores are used to store information about networks of data, such as
  social connections. Graph stores include Neo4J and Giraph.
- Key-value stores are the simplest NoSQL databases. Every single item in the
  database is stored as an attribute name (or 'key'), together with its value.
  Examples of key-value stores are Riak and Berkeley DB. Some key-value stores,
  such as Redis, allow each value to have a type, such as 'integer', which adds
  functionality.
- Wide-column stores such as Cassandra and HBase are optimized for queries over
  large datasets, and storecolumns of data together, instead of rows.


NoSQL databases are built to allow the insertion of data without a predefined
schema. That makes it easy to make significant application changes in real-time,
without worrying about service interruptions – which means development is
faster, code integration is more reliable, and less database administrator time
is needed.

Because of the way they are structured, relational databases usually
scale vertically – a single server has to host the entire database to ensure
acceptable performance for cross- table joins and transactions. This gets
expensive quickly, places limits on scale, and creates a relatively small number
of failure points for database infrastructure. The solution to support rapidly
growing applications is to scale horizontally, by adding servers instead of
concentrating more capacity in a single server.

 
