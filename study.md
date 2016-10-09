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

NoSQL is an umbrella term that refers to a variety of different, non-relational
databases.

Types of NoSQL databases include:

Document Databases pair each key with a complex data structure known as a ‘document'
       Documents can contain many different key-value pairs, key-array pairs, or even nested docs.
  Graph stores are used to store info about networks of data, such as social connections
       > Neo4J and Giraph are examples of graph stores
  Key-value stores are the simplest NoSQL databases. Every single item in the db is stored as an attribute name (‘key’) together with its value
       > Riak, Berkeley DB, and Redis are examples of Key-value stores
  Wide-column stores are optimized for queries over large datasets , and store columns of data together, instead of rows
       > Cassandra and HBase are examples of these.

Relational databases store things in a table, with the data stored as rows and each column
corresponding to a specific type of data.

One common kind of NoSQL database, a key-value stores, stores only two columns - a 'key' and a 'value'
Document databases, like MongoDB, don't have a table/row model at all, and store the data togehter in a single 'document' in JSON (or XML, or...) format with nested values.

In relational databases, like SQL, the datatypes and schema must be defined _before_ we can add data.
  Every time we need to add new data, we'll need to migrate the database which can cause significant downtime with larger dbs.
In NoSQL databases, we can insert the data without knowing the predefined schema, allowing things to be faster and more flexible.

NoSQL databases also support automatic 'sharding', or distributing the database over multiple servers, often cloud-based. This can be cheaper, and easier than buying dedicated servers, as well as making sure no one server gets overloaded, or, if it goes down, the entire application won't be affected.

NoSQL databases are also 'object oriented,' meaning they can be accessed and manipulated through object oriented APIs, as opposed to SQL-based language statements.


A relational database stores your data in tables made out of rows
MongoDB stores your data in collections made out of documents

Relational databases are best used when we know the type of our data, and it likely won't change. We just need to put data in and take data out, with maybe a few simple 'joins' throughout.

Nonrelational databases are much better for flexibility and scalability, allowing for cheaper maintenance and adjustments. If we are not sure what kind of data we'll need, or that data will likely often change, we should use a nonrelational database.
