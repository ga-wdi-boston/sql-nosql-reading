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

Use cases:
Most large databases could benefit from NoSQL databases because relational ones
create migrations every time a column is added and that's time consuming. Also,
peace of mind since most NoSQL databases support replication: they are fully
self-healing, offering automated failover and recovery.
Uses of relational databases include the fact that it reduces nesting errors
and duplicate data. The example cited on one of the reading is social media apps
and how it is impossible to construct an activity stream from a single document
and this is less efficient and complex. Finally, understanding where in your
data the business value lies. 'While pushing arbitrary json is flexible, the
flexibility is easily adding features or business needs.'
NoSQL databases have a few strengths such as being more scalable: agile sprints,
quick schema itiration, and frequent code pushes. Also, object-oriented
programming: easy to use and flexible. Finally, dynamic schemas make code more
reliable, and during maintenance, there's no need to put the database offline.
SQL databases also have strengths. They can be configured for strong
consistency. They also have specific language using Select, Insert, and Update
statements, e.g. SELECT fields FROM table WHERE… this allows for uniform code.
Finally, SQL databases were developed in 1970s to deal with first wave of data
storage applications, which makes them successful through time as they are still
around and documentation is bigger.
