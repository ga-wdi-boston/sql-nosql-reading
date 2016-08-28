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
Identify use cases where relational or non-relational databases are appropriate.
Relational: If the informaion in the database links to other information in the databse.
Non-Relational: If you have alot of varying information that does not need to link to other informaion.

List three strengths of relational databases.
reliable, no duplicate info, validation
List three strengths of non-relational databases
fast, flexible data storage, shards

---

SQL seems like the overall better option and mongoDb is more of a specialized tool than a database that you should just use in whatever you're working on. When reading through the mongodb site it seemed like it was better than SQL in every way, but after reading Sarah Mei's article I can see some of the limitations of mongo (a rather large limitation imo). Sharding seems like a really usefull feature, but I don't know how useful it would be if all of the data is arbitrary JSON that doesn't link to anything. (also, is mongo supposed to save space or take up alot of hdd space? It seems to me that b/c you shouldn't link the documents you'd have to write the same information many times.) Also, from the MongoDb is web scale video, he mentioned that when you write to the mongo database you actually stage your data to be written at a later time. This sounds terrible to me and completly counter to what you want from a database. Overall, I think I prefer the SQL database over mongoDb.

---
<!--
Notes:
NoSQL Database Types

Document databases pair each key with a complex data structure known as a document. Documents can contain many different key-value pairs, or key-array pairs, or even nested documents.
Graph stores are used to store information about networks of data, such as social connections. Graph stores include Neo4J and Giraph.
Key-value stores are the simplest NoSQL databases. Every single item in the database is stored as an attribute name (or 'key'), together with its value. Examples of key-value stores are Riak and Berkeley DB. Some key-value stores, such as Redis, allow each value to have a type, such as 'integer', which adds functionality.
Wide-column stores such as Cassandra and HBase are optimized for queries over large datasets, and store columns of data together, instead of rows.


The Benefits of NoSQL

When compared to relational databases, NoSQL databases are more scalable and provide superior performance, and their data model addresses several issues that the relational model is not designed to address:
Large volumes of rapidly changing structured, semi-structured, and unstructured data

Agile sprints, quick schema iteration, and frequent code pushes

Object-oriented programming that is easy to use and flexible

Geographically distributed scale-out architecture instead of expensive, monolithic architecture


Dynamic Schemas

NoSQL databases are built to allow the insertion of data without a predefined schema.


Auto-sharding

The solution to support rapidly growing applications is to scale horizontally, by adding servers instead of concentrating more capacity in a single server.

NoSQL databases, on the other hand, usually support auto-sharding, meaning that they natively and automatically spread data across an arbitrary number of servers, without requiring the application to even be aware of the composition of the server pool. Data and query load are automatically balanced across servers, and when a server goes down, it can be quickly and transparently replaced with no application disruption.


Replication

Most NoSQL databases also support automatic database replication to maintain availability in the event of outages or planned maintenance events. More sophisticated NoSQL databases are fully self-healing, offering automated failover and recovery, as well as the ability to distribute the database across multiple geographic regions to withstand regional failures and enable data localization. Unlike relational databases, NoSQL databases generally have no requirement for separate applications or expensive add-ons to implement replication.




Don’t. Link. The. Documents.
Once we started doing ugly MongoDB joins manually in the Diaspora code, we knew it was the first sign of trouble. It was a sign that our data was actually relational, that there was value to that structure, and that we were going against the basic concept of a document data store.

Whether you’re duplicating critical data (ugh), or using references and doing joins in your application code (double ugh), when you have links between documents, you’ve outgrown MongoDB. When the MongoDB folks say “documents,” in many ways, they mean things you can print out on a piece of paper and hold. A document may have internal structure — headings and subheadings and paragraphs and footers — but it doesn’t link to other documents. It’s a self-contained piece of semi-structured data.

If your data looks like that, you’ve got documents. Congratulations! It’s a good use case for Mongo. But if there’s value in the links between documents, then you don’t actually have documents. MongoDB is not the right solution for you. It’s certainly not the right solution for social data, where links between documents are actually the most critical data in the system.

So social data isn’t document-oriented. Does that mean it’s actually…relational?


Always Be Learning
I learned something from that experience: MongoDB’s ideal use case is even narrower than our television data. The only thing it’s good at is storing arbitrary pieces of JSON. “Arbitrary,” in this context, means that you don’t care at all what’s inside that JSON. You don’t even look. There is no schema, not even an implicit schema, as there was in our TV show data. Each document is just a blob whose interior you make absolutely no assumptions about.

At RubyConf this weekend, I ran into Conrad Irwin, who suggested this use case. He’s used MongoDB to store arbitrary bits of JSON that come from customers through an API. That’s reasonable. The CAP theorem doesn’t matter when your data is meaningless. But in interesting applications, your data isn’t meaningless.

I’ve heard many people talk about dropping MongoDB in to their web application as a replacement for MySQL or PostgreSQL. There are no circumstances under which that is a good idea. Schema flexibility sounds like a great idea, but the only time it’s actually useful is when the structure of your data has no value. If you have an implicit schema — meaning, if there are things you are expecting in that JSON — then MongoDB is the wrong choice. I suggest taking a look at PostgreSQL’s hstore (now apparently faster than MongoDB anyway), and learning how to make schema changes. They really aren’t that hard, even in large tables. -->
