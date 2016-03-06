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
  Relational databases are widely used for projects that don't require a huge amount of versatility
in the things you will actually be storing. Non-relational have much more flexibility as far as changing te actual data stored and are therefore great for things like e-commerce or 'content management' (blog, social media etc.) apps that may require different pieces of data to be shown all relating to one thing.

Three strengths of NoSQL databases:
  1. Never having the problem of "impendance mismatch". Since pieces of data are not stored in the in one "document", you will never have to worry about join-tables and foreign keys and making all the data work together from different tables.
  2. Being able to store many attributes of one piece of data easily rather than the simple one key, one value system that SQL databases implement.
  3. Better scalibility. Related to the "impendance mismatch", if an app is scaling a quick rate it won't matter too much because each piece of related info is stored together and the DB won't have to account for more and more complicated and synchronous tables joins.

Three strengths of SQL databases:
  1. Limit the amount of repeat data. Since data is stored in one table and is then linked to other tables it cuts out the need to repeat yourself since the data is linked naturally.
  2. Complicated queries are easy to achieve. The way that the data is stored allows for complicated queries through SELECT and broken down further into WHERE can easily dig deep into the database to return only relevant information for the task at hand.
  3. Ease of use and implementation. It's a simple system of rows and columns at its core. Of course, it gets more comolicated but with a well thought plan of attack. The appropriate database system to last throughout the project at hand can be achieved rather easily.
