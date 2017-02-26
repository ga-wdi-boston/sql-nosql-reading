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

SQL/relational databases are most appropriate when relationships are known up front and data integrity is important e.g. project two & library example.
"When MongoDB is all you have, it’s a cache with no backing store behind it. It will become inconsistent. Not eventually consistent — just plain, flat-out inconsistent, for all time. At that point, you have no options. Not even a nuclear one. You have no way to regenerate the data in a consistent state." http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/


NoSQL/non-relational databases are most appropriate when there are large volumes of rapidly changing (structured, semi-structured, and unstructured) data  that is self contained (not duplicative) e.g. for storing information for product data management and e-commerce websites and solutions. Another example: tv shows with many seasons/episodes/cast/comments (12000 load in seconds vs a minute)...until the client wanted to be able to see all of a cast member's work (http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/).



SQL/relational databases are 1) well established and more mature and understood by developers/admins, 2) data integrity is strong (not caching) and 3) relationships reduce duplication (users > friends, commenters, likers)

NoSQL/non-relational databases are 1) more scalable (sharding over multiple servers) and are 2) able to be utilized for agile sprints and frequent code pushes. They can also 3) handle large volumes of rapidly changing structured, semi-structured, or unstructured data.
