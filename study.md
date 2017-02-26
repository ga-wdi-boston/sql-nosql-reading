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

-   Identify use cases where relational or non-relational databases are
    appropriate.
Internet of things, real-time analytics, single view all use non relational databases.
Our 2nd project used relational database.


-   List three strengths of relational databases.
1. Many benefits of the relational database, such as transactional integrity, are compromised or eliminated when employing manual sharding.
2. Users need to enter each piece of data only once, which minimizes the size of the database as well as the likelihood of mistakes.
3. Each line of data, or record, has a unique identifier that serves as a relational key that makes it easy to locate data when a user needs to access a record.
4. Multiple users can access the data with individual permissions that protect the security of the database.



-   List three strengths of non-relational databases.
1. Can effectively address data that's completely unstructured or unknown in advance. NoSQL databases are built to allow the insertion of data without a predefined schema.
2. Usually support auto-sharding, meaning that they natively and automatically spread data across an arbitrary number of servers, without requiring the application to even be aware of the composition of the server pool.
3. Generally have no requirement for separate applications or expensive add-ons to implement replication.
4. more scalable and provide superior performance, and their data model addresses several issues that the relational model is not designed to address:
Large volumes of rapidly changing structured, semi-structured, and unstructured data
Agile sprints, quick schema iteration, and frequent code pushes
Object-oriented programming that is easy to use and flexible
Geographically distributed scale-out architecture instead of expensive, monolithic architecture
