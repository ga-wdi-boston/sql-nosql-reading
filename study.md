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

### [NoSQL Databases Explained | MongoDB](https://www.mongodb.com/nosql-explained)

NoSQL dbs scale better, are more agile, and take advantage of modern storage and processing capabilities. They're more scaleable/perform better.

Other benefits:
  - handle large volumes of rapidly changing data (structured, semi-structured, and unstructured)
  - SQL dbs usually have to be stored on single server. means you have to "vertically" scale (add more power to single server) rather than spreading horizontally across multiple servers (which is possible but complicated & time-consuming).
  - NoSQL dbs handle "sharding" (splitting across multiple servers) better: they use "auto-sharding, meaning that they natively and automatically spread data across an arbitrary number of servers." your app doesn't have to know details about or manage these servers. geographically distributed servers are cheaper than single powerful server.
  - handle agile sprints, quick schema iteration, and frequent code pushes (hard when you have to define schema ahead of time, like in SQL—have to write & run another migration before you can add data. with large databases, this can cause extensive downtime)
  - offer object-oriented programming that is easy to use and flexible
  - replication: easier/faster/often native
  - integrated caching (rather than expensive 3rd party services)

Four kinds of NoSQL dbs:
  - document dbs: keys are paired with "documents," which can hold multiple key-value pairs, key-array pairs, or other documents. (basically: JSON)
  - graph stores: store info about networks of data (social connections)
  - key-value stores: the simplest. all items in db are key:value
  - wide-column stores: store columns (instead of rows); optimized for large dataset queries

https://docs.mongodb.com/ecosystem/use-cases/hierarchical-aggregation/ -- example of memoizing, yes?

### [Why You Sould Never Use MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/)

MongoDB (and presumably many NoSQL dbs?) is a cache—it will become inconsistent, and there's no way to fix that.

MongoDB doesn't have join capabilities. Have to write code in your application to connect/retrieve entities. (Or to duplicate data, but that's a bad idea in general for consistency's sake.)

Most data is relational, so you should use a relational db. NoSQL is only okay if you truly (really, honestly, actually) don't care about what your data is and aren't expecting certain things to be in it.
