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

* NoSQL
  * Encompasses a wide variety of database techniques
  * Developed in response to the demands of building modern applications
  * Database types:
    * Document databases: pair each key with a complex data structure (aka a document)
    * Graph stores: store information about networks of data
    * Key-value stores: simplest type. Each item in the database has an attribtue name (key) and a value
    * Wide-column stores: optimized for queries over large datasets
  * Benefits:
    * NoSQL databases are more scaleable than relational databases and provide superior performance.
    * They are designed for large volumes of rapidly changing, structured, semi-structured, and unstructured data.
  * Dynamic schemas:
    * Relational databases require that schemas be defined before you can add data
  * Auto sharding:
    * Allows databases to scale horizontally across many servers
  * Examples:
    * MongoDB, Cassandra, HBase, Neo4j
* mongoDB use cases:
  * MongoDB’s flexible schema makes it particularly well suited to storing information for product data management and e-commerce websites and solutions.
  * operational intelligence and real time analytics use
  * content management system (CMS)
    * storing data like users comments on content
  * Instead of storing your data in tables made out of individual rows, like a relational database does, it stores your data in collections made out of individual documents.
  * What’s missing from MongoDB is a SQL-style join operation, which is the ability to write one query that mashes together the activity stream and all the users that the stream references.
  * MongoDB makes sense for data that requires no joins (tv shows), vs. a social network
  * when you have links between documents, you’ve outgrown MongoDB.
  * When the MongoDB folks say “documents,” in many ways, they mean things you can print out on a piece of paper and hold. A document may have internal structure — headings and subheadings and paragraphs and footers — but it doesn’t link to other documents. It’s a self-contained piece of semi-structured data.
