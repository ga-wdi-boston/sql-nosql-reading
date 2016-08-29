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

There are many differences between relational and non-relational database structures.
Relational dbs are built with the schema predefined, and adding any new data columns will necessitate a data migration.  This causes database downtime, which may be a serious problem with an application that requires agility.
Non-relational databases store information that is structured, semi-structerd or unstructured.  The information is stored as BSON, and is stored as a document that can hold any amount of different key-values without any problems.

Relational databases are designed to grow vertically, where all of the data is stored on one server.  Spreading data across multiple servers can be challenging.  Non-relational data is designed for sharding across different servers, and can be setup for auto-sharding , which will automatically make these transfers across servers.

With relational databases, if there are two tables of data, no record can be made of the referencing table unless a foreign key relates to the id number of the thing its relating to.  In non-relational databases this does not occur and any data can be stored as a value as long as the data's id value is valid.

Non-relational data is preferred if pre-defining data will be difficult and constant changes to keys or columns are likely.
However, relational databases can be easier to control relationships with different data tables through join tables.  NoSQL needs to be related manually, as well as manually creating transactions.  Relational databases are a better option for complex connections between different data types.  This becomes less of a clear advantage when the scale of the database moves beyond the capacity of a single server, since realational databases are move difficult to scale out horizontally.
