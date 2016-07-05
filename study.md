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
Identify use cases where relational or non-relational databases are appropriate.

Relational DBs are most useful for traditional data that is best stored in
tables with rows and columns, like spreadsheets.

Non-relational databases are useful when the data is particularly large, rapidly changing, semi-structured/unstructured.

Non-relational databases are also easier to use for agile teams.
Migrations are not required when the data changes.

Non-relational databases are also more
scalable across commodity hardware.

Mongo example non-relational databse examples included operational intelligence, product data management, CMS.

List three strengths of relational databases.
Relational databases keep the size of the data small by not replicating data, allow you to use arbitrary joins to get more complex data while maintaining the integrity of the data, use caching to work more quickly.

List three strengths of non-relational databases.
They are often more flexible across different and changing data types, they are often more scalable horizontally across commodity hardware. They can often get data without doing joins, so much more quickly. This fails once you want to use the meaning and links between the entities at lower levels of the hierarchies in whatever structures you are using though.
