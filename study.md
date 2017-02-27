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

SQL databases store relationships well
keep data organized and accessible between relationships
handles lots of data more easily (if slowly)


Non-SQL databases are more scalable than SQL ones
Allow for faster insertion of data since they do not require schema migrations
Can easily spread data across servers

a MongoDB document is a blob of JSON - easy to get out
construction activity stream by id requires making secondary calls to those id's
joins are ugly and front end with MongoDB
cache is an inbetween data store that gets refreshed from the server sometimes but is generally just appened to - makes things a lot faster than calling the server each time
