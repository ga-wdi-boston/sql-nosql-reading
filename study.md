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

Types of data are structured, semi-structured, unstructured and polymorphic. Types of NoSQL databases are document databases, graph stores, key-value stores and wide-column stores. NOSQL databases are better than relational databases for large volume, frequently pushed, object oriented programming projects. NoSQL database schemas can be changed and the databases support auto-sharding as well as automatic replication.

Mongo DB, a non-relational database, is good for product data management and e-commerce as well as website content management (i.e. storing comments).  MongoDB has collections made of documents, not tables made of rows and uses nested hashes to store data.  

Diaspora has hundreds of independent servers (aka pods) which each have their own database that communicates to other pods through an API.  If one pod goes down, others will not follow suit.
Each pod is a Ruby on Rails app.
