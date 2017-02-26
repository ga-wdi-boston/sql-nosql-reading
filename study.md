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

Appropriate use cases:

-   Inventory management (inventory, carts(active and stale states))
-   Product catalog
-   Category hierarchy

Inappropriate use cases:

-   Diaspora (social networks)
-   When the structure of your data has value

Strengths:

-   Fast
-   Horizontal (operations can be spread across multiple servers) / not
vertical (meaning increasing processing power on one server, which can be
prohibitively expensive, is not required).
-   Works well with today's workplace development strategy, Agile. No schema
needed. Changes can be made more easily/quickly. Underlying data model not
required prior to populating database.

Weaknesses:

-   Advantages fall apart when relationships between documents are required.
-   Cache invalidation becomes difficult, and lack of a backing store means you
don't even have a nuclear option (wiping data and regenerating from backing
store); this means data will eventually become inconsistent and you have no way
to regenerate.
-   Can make adding future features difficult, e.g., while your data may not
need relationships at the start of the project, future features may require
relationships/links, meaning MongoDB/NoSQL's benefits are no longer applicable
for you.
