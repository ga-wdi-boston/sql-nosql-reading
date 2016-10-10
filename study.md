# Relational and Non-relational Databases Study

Read the following articles thoroughly. Practice active reading by taking notes.

-   [NoSQL Databases Explained | MongoDB](https://www.mongodb.com/nosql-explained)
-   [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/) (click
    through to at least one detailed example)
-   [Why You Sould Never Use MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/)

As you read, pay special attention to addressing the following:

-   Describe a few differences between relational and non-relational stores.

     - non-relational stores are more scalable than relational ones.
     - non-relational stores are better able to handle rapidly changing data.
     - non relations stores have more options for structuring the data.

-   List the stengths and weaknesses of relational and non-relational stores.
     -  a benefit of using non-relational stores is that you are able to change the schemas by
          the tables during production without re creating them, such as adding new columns to
          sort your data by.
     -  non-relational stores are more easy to scale horizontally across multiple servers
           because of the autosharding feature.
     - most non-relational stores also support automatic database duplication. The data is
          considered more localized with relational stores.
     - Non-relational databases provide better integrated cacheing, without adding the
          complexity that relational databases do.

-   List criteria that can help someone choose between relational and
    non-relational stores.
    - What kind of data are you working with? Will it continue to expand or change?
    - What is your timeline for producing the data tables?

After you've finished your study, summarize your notes to the following section
and open a pull request.

Types of SQL databases (relational stores) :
  - MySQL, Postgres, Microsoft SQL Server, Oracle Database

Types of NonSQL databases (non-relational stores) :
  - MongoDB, Cassandra, HBase, Neo4j

NoSQL Database Types - Document databases, graph stores, key-value stores, wide-column stores.

Mongo DB is a non relational database that stores data in collections made up of documents,
instead of tables made up of rows.

"the most important thing to understand is where in your data —
and where in its connections — the business value lies"

Terms to know:
Cache - component that stores data so future requests for that data can be served faster.
Sharding - method for distributing data across multiple servers.
Blobs(Binary Large Object) - a collection of binary data stored as a single entity in a database management system.
Documents - Blobs made up of JSON.


Be prepared to share your notes with others before the discussion. Everyone
should have something to contribute.

## Summary

<!-- your notes here -->
