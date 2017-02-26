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

NoSQL:
built to better support modern developers
- Designed to better handle large volumes of datasets (all types of structures)
 - & allow for insertion of data without a predefined schema
- & to better support rapid changes (agile development, frequent pushes)
- object oriented
- 'Auto-sharing': natively and automatically spread data across an arbitrary number of servers, without requiring the application to even be aware of the composition of the server pool. & balance across servers in case one goes down
- stores data horizontally - which allows for simpler scaling

- Problems with relational databases: not scalable, don’t support agile development, less storage/processing power, shames need to be determined in advance

Database types:
Document
     - pair each key with a complex data structure known as a document. Documents can contain many different key-value pairs, or key-array pairs, or even nested documents.

Graph stores
     - store information about networks of data, such as social connections

Key-value
      - simplest NoSQL databases. Every single item in the database is stored as an attribute name (or 'key'), together with its value

Wide-column stores
     -  optimized for queries over large datasets, and store columns of data together, instead of rows.

Use cases:
Product management - eCommerce product catalog example (inheritance vs. multiple values & no need for join)
Storing log data - storage engine for log data from servers and other machine data
Content management system - storing comments, etc.
