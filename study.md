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
In sql, join tables will begin to process slower with more and more information in them. Since relational database cannot process large amount of data, more applications make use of non-relational databases. If using a relational database, you must plan ahead for data you may want to store in the future. Since relational databases host the entire database, there a limits on scale and it can be expensive. Non-relational databases scale horizaontally, which is cheaper and more simple than vertical scaling. When manually sharding with a relational database, some benefits are compromised or eliminated but non-relational databses, usually support auto-sharding which is spreading data across multiple servers.

Relational Databases
transactional integrity
individual records(multiple columns)
vertical scaling
mix of open and closed sourcing

Non-Relational Databases
 More reliable and have a better performance for large amounts of data, frequent changes in code, object-oriented programming, etc.
 Better for agile development.
 Allow the insertion of data without having to define the schema in advance.
 support auto-sharding
 support automatic database replication which maintains availability in case there are outages or maintainence.
 key, value stores (only two columns, key and value)
 horizontal scaling
 open source
