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
Relational databases are more appropriate when the relationships between the data are clear and important and the links have value, too. Their ability to link things with join tables and foreign keys are hard to replicate in a non-relational database.

Non-relational databases are more appropriate when dealing with large amounts of data, or data that needs to rapidly change in ways that would necessitate migrations in a relational database. Data should also be non-relational at heart--the links between the pieces of information shouldn't matter so much, and the value should be in the documents themselves.

Relational databases:
Have join tables to make cleaner relationships (if the relationships are clean to start with).
Data is less likely to become inconsistent because if something is updated, it only needs to be updated in one place (its row) due to all links being done by ids, foreign keys and join tables.
There is no need to ever duplicate data (because, once again, foreign keys).


Non-relational databases:
Schemas do not have to be defined before adding data. If you want to add new information during production, the whole database doesn't have to be migrated to incorporate a new column.
Are more flexible with scaling. The data can be split across multiple servers to increase speed.
Can replicate data easily and some can "self-heal".
