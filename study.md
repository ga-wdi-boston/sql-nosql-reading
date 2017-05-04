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

MongoDB's website talks about some examples of the strengths of non-relational databases.

One strength is flexibility and ease of use.  A relational DB requires a schema created in advance in order to function.
Non-relational DBs can store data of many different types and structures without building anything in advance.

In addition, non-relational databases are more scalable.  Non-relational DBs can store large quantities of data that would be
impractical for a relational databse.

NoSQL databases are also very good at distributing data, called auto-sharding, horizontally across servers with cloud computing.
Relational databases usually have to scale vertically on one growing server.

NoSQL apps can sometimes have automatical replication in the event of bugs, errors or outages.

In SQL and relational databases in general data is stored in rows with predefined fields and schemas.  NoSQL databases can have
their data structured in a variety of different ways.  NoSQL databases can have dynamic schemas.

Reading the case study about comments and learning about the document type of object.  Similar to JSON but more dynamic.

If you were storing user comments for a web site, giving each comment its' own document is suitable if you need to get the comments
in chronological order but not much else.

Threaded comments would have a parent ID field referring to the parent comment.

In the final article, the author makes a convincing case to stick with relational database with any dataset that is structured.
Specifically, NoSQL is only a good idea if your pieces of data are completely self-contained.  That is certainly not the case with
my apps or most others.  The post emphasizes the consequences of duplicating the same pieces of data without a real schema or structure to
identify them or link them together.
