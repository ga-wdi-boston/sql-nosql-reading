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

As you read, pay special attention to addressing the following:

* Identify use cases where relational or non-relational databases are appropriate.
    * relational
        * if your application doesnt use documents
        * if you dont expect your data or user base to grow significantly
        * if join tables are central to your application, many relations are present
        * When you are relying on the JSON that is returned from the server (if you have a implicit schema)
    * non relational
        * if data introduced into the db is dynamic, changing all the time
        * if you’re expecting the application to increase in popularity soon, as non-relational databases allow for excellent scalling
        * product data management
        * content management systems
        * if you have documents
        * if you’re using join tables or have many relationships between data
        * store arbitrary bits of JSON that come from customers through an API
* List three strengths of relational databases.
    * data is only stored once which allows the data to be more easily changed, removed, or added
    * complex data queries can be carried out
    * allows for different data to be accessed simultaneously
* List three strengths of non-relational databases.
    * more scaleable
    * provide superior performance over non-relationable databases
    * does not require a schema be defined before data is added - can speed up time that database is down for updates
    * can address data thats unstructured or unknown in advance
    * application changes can occur in real time which allows for faster development, more reliable code integration, and less database administration
    * validation rules can be applied within the database, which allows users to enforce governance accross data while maintaining the agility benefits of a dynamic schema

Why was noSQL developed?
    apps create massive amounts of data of different types
    development teams push code much more often than in the past
    apps must always be accessable to users and also must be scalable as the application grows in popularity
    more applications are using cloud servers as opposed to having on-side server farms

relational databases were not designed to cope with these modern needs.

MongoDB = leading non-relational database

noSQL database types:
    document databases: each key is paired with a document
    graph stores: used to store information about networks of data, such as social connections
    key-value stores: simplest NoSQL databases. each item in the db is stored as an attribute name (key) together with its value
    wide-column stores: optimized for queries over large datasets. store data in columns instead of rows

Benefits of NoSQL:
When compared to relational databases, NoSQL databases are more scalable and provide superior performance, and their data model addresses several issues that the relational model is not designed to address:

*
Large volumes of rapidly changing structured, semi-structured, and unstructured data

*
Agile sprints, quick schema iteration, and frequent code pushes

*
Object-oriented programming that is easy to use and flexible

*
Geographically distributed scale-out architecture instead of expensive, monolithic architecture


NoSQL databases are designed to be built to allow the insertion of data without a predefined schema - allows for significant application changes in real-time without worrying about service interruptions.

Auto-sharding:
    noSQL databases natively and automatically spread data across an arbitrary number of servers without require the application to be aware of the composition of the server pool. if one server goes down other servers can pick up the slack and the application can remain online.

replication:
most NoSQL databases support automatic database replication to maintain availability in the event of outages or planned maintenance. Most NoSQL databases also offer automated failover or recovery, along with the ability to distribute the dbs across multiple regions to withstand regional failures or to enable data localization. Also NoSQL databases do not require separate applications or expensive add-ons to implement replication

Integrated Caching:
many have excellent integrated caching capabilities allowing for frequently used data to be kept in system memory as much as possible while removing the separate caching layer.
