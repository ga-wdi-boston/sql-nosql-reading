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

NoSQL databases have an advantage over traditional relational databases in that
they are able to deal with unstructured or semi-structured data, respond well to
agile methodologies (sprints, frequent code changes) and allow more distributed
server structures through sharding and geographic distribution. They allow
databases to be constructed without predetermined schema, so alteration to a
db's structure can be implemented without interruprting service to users. They
support using multiple data structures, from simple key-value stores, document
databases, graph dbs and wide-column stores (which make dealing with queries for
large sets of data simpler).

HOWEVER, from the third reading it seems awfully easy to misinterpret a NoSQL
database's proper use. When your entity relationships require a clear
heirachical structure, a traditional relational database might be a better
choice.
