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

Mongo DB is a document database that works stores data using hash and keys
rather than tables and column like relational database. It is basically
a fractal data structure.

## Strengths

Instead of tables information is stored on one document.  This means it is
really fast to spit out data all at once.

It also grows the database horizontally across multiple servers and not just
one. It uses a method called sharding.

It can kind of serve as a backup onto itself, if one server goes down it can
quickly recover by pulling in data from other servers.

## Weaknesses

The use of mongo seems to be very limited because linking often runs into
trouble.

The data stored is unreliable cause everything is cached data and doesn't
neccessarily have a backing store. And what if the data being recorded fails,
you are so screwed.

It stages data to be written at a later time, so if the data written fails you
will have no idea if it failed.
