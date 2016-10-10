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

- Relational databases are useful when you have nested data where subsets are of the same type as any ancestor set.  This way you can store a reference to the subset inside the parent set without duplicating the data itself.
- SQL databases are also fairly ubiquitous, so they are useful in the sense that pretty much everyone knows how to use them and there are a lot of good resources for learning how to use them.
- Queries are still very fast, even though modifying the database itself can take some time depending on what you're doing.

- Non-relational databases can be more easily delocalized across many servers.
- NoSQL databases can also be more flexible if you're working with data that's poorly defined or whose schema changes rapidly because you do not need to migrate your ENTIRE database each time you want to add or change a relationship.
- There are many more options for modeling your data, i.e., with a graph-model, document-model, wide-column, or the standard SQLesque key-value model.
