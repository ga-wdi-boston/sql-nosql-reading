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

Relational databases are not good at handling the stresses of the server demand of current applications, so non relational databases are used.

Non-relational databases (NoSQL) are:
* More scalable
* higher performance
* Can deal with quicker, more frequent code production
* can change or add data without having to first add it to the schema
* balances server load over a large number of servers
* information can be accessed quickly because all the information about a thing is stored in a json string in the same place

Using relational databases vs non-relational databases depends on the nature of the data to be stored.  If your data is, say, a dictionary, the each word has data accompanying it (etymology, definition, etc).  This data does not reference other tables, so it is not relational in nature.  So, using a non-relational database would be advantageous.  If the data was from a social network, we would expect the data to need to reference many other tables, because users have many ways to interact with each other.  This type of data works better with a relational database.

Relational databases are:
* more consistent.  non-relational database is a cache with no backup, so you can’t ‘nuke-pave’ if your data becomes inconsistent
* It is much easier to add relationships between data with a relational database
* When changes are made (a feature) it is easy to make changes in the whole database because of relationships
