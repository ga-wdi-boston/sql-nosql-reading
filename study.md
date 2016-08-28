# Relational and Non-relational Databases Study

Read the following articles thoroughly. Practice active reading by taking notes.

-   [NoSQL Databases Explained | MongoDB](https://www.mongodb.com/nosql-explained)
-   [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/) (click
    through to at least one detailed example)
-   [Why You Sould Never Use MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/)

As you read, pay special attention to addressing the following:

-   Identify use cases where relational or non-relational databases are appropriate.

RDBMS are more appropriate when you can't afford to lose any information or have it not be exact. Also, Join tables.

NRDBMS are a lot better for updating the database without having it be inactive so that users can always access it.

-   List three strengths of relational databases.

1 Data is kept intact and exactly accurate
2 More robust query language
3 RDBMS are ACID compliant
(Atomicity - each transaction is all or nothing, if one part of the transaction fails, then the entire transaction fails. The database goes back to where it was before the transaction began. This is especially important for unexpected things like power failures, or crashes.)
(Consistensy - ensures data validity.)
(Isolation - protects against two transactions from attempting to affect the same data at once.)
(Durability - ensures that once a transaction has occured, the data is now permanently stored in its new spot.)


-   List three strengths of non-relational databases.

1 Much more scalable than RDBMS
2 Easily use multiple servers
3 Can update in real time without disrupting servers

After you've finished your study, summarize your notes to the following section
and open a pull request.

Be prepared to share your notes with others before the discussion. Everyone
should have something to contribute.

## Summary

<!-- your notes here -->
- RDBMS have been around for much longer which means they are more stable and have better documentation out there. This also means that they were designed for a different time so they won't always be the best answer to every database problem.

- NoSQL databases were designed to face the more modern issues faced by programmers. They are much more scalable and are faster than their SQL counterparts

- Relational databases require that schemas be defined before adding data. Updating the schema requires downtime for the database and means the entire database must be changed before adding a new data type.

- NoSQL databases can have data inserted into them without a defined schema beforehand

- Spreading a database out amongst multiple servers is much easier to achieve with a NoSQL database

- NoSQL can also store things like images, and documents within documents
