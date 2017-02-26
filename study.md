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


- A different database technology which provides superior performance.
- Mongo DB is the leading non-relational database
- There are four types of NoSQL databases
    * Document database: Each key is paired with a document.
    * Graph store: Used to store graphs produced by social network analysis.
    * Key-value-store: Every data in the database is a key with a value.
    * Wide-column-store: Can handle a large number of nodes.

Relational Database

- In relational databases like SQL, the schema needs to be defined first with the attributes before inputing data.Adding new attributes to the database will result in constant repetitive migration processes to renew the schema.
- Code to enforce data quality control (presence of fields, permissible values)
- A server hosts the database - scale vertically

No SQL database
- No need of a predefined schema to input data
- Validation rules are applied within the database
- Data is spread to a number of severs (commodity servers) - scale horizontally
- Support automatic database replication
- Data manipulation done through object-oriented APIs

"Schema flexibility sounds like a great idea, but the only time it’s actually useful is when the structure of your data has no value. If you have an implicit schema — meaning, if there are things you are expecting in that JSON — then MongoDB is the wrong choice."
