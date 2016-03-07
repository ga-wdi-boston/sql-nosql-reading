# Relational and Non-relational Databases Study

Read the following articles thoroughly. Practice active reading by taking notes.

-   [NoSQL Databases Explained | MongoDB](https://www.mongodb.com/nosql-explained)
-   [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/) (click
    through to at least one detailed example)
-   [Why You Sould Never Use MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/)

As you read, pay special attention to addressing the following:

-   Identify use cases where relational or non-relational databases are
    appropriate.

For websites that manage *big data* like Facebook, Google and Amazon, non-relational database is more appropriate due to its scalability and efficiency.

Relational database is useful if you are building low-volume, medium complexity web app like our Project 2.

-   List three strengths of relational databases.

Proven legacy technology with stable code base

Easier to write SQL queries vs programming skills to code in NoSQL systems.

Normalization - data is organized in a database where relationships are enforced with constraints, ie primary and foreign keys. This provides entity and referential integrity between/among multiple tables, eliminate duplicacy and inconsistency.

-   List three strengths of non-relational databases.

Scale out - can handle large amount of data without using a lot of disk space.

Handle unstructured and semi-structured data - allows for more flexibile schema and datatypes (like JSON).

Eventual consistency - data is replicated/distributed on multiple servers, allows for low-latency reads. Any changes to data will *eventually* be updated across all servers so the users will have the up-to-date copy.




After you've finished your study, summarize your notes to the following section
and open a pull request.

Be prepared to share your notes with others before the discussion. Everyone
should have something to contribute.

## Summary

[Relational vs NoSQL Databases](https://www.youtube.com/watch?v=XPqrY7YEs0A)
[Eventual Consistency](http://stackoverflow.com/questions/10078540/eventual-consistency-in-plain-english)
