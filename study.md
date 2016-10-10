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

- It's really important to know the types of data you're using before choosing
a database type
- Both types can adopt features of the other, but it's much easier to choose
just one.


Q 1: Relational databases work best in contexts where the data-types and schema 
are known and defined when the database is created. An example is our patient-clinic
database, where we know at the outset what types of data we want, and thus there
is no frequent need to change the structure of the database.
Non-relational databases work well in situations where data is rapidly changing,
and thus requires more flexibility. An example would be a Netflix profile

Q 2:

Pros of Relational:
Allow for relationships (duh)
Better for making large scale changes
Limit redundancy and duplication

Q 3:

Pros of Non-relational:
Allow faster load times and are more scaleable
Cheaper and easier to maintain
Can be sharded scross several servers
