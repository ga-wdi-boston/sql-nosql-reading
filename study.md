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
Strengths of relational databases:
1. Better for simpler data structures (tables)
2. They limit redundancy
3. Because it's not dynamic, data is always stored in the same place.

Weakenesses of relational databases:
1. Poorly represent "real world" entities
2. Aren't suited for complex data types
3. Difficulty implementing recursive queries (ie searching the same table
 more than once).

Strengths of non-relational databases:
1. Better for large data structures and large amounts of complex data
2. Good for more complex relationships, such as in social data when
  an entity may theoretically be represented in more than one place (ie, "user",
  "liker", "commenter")
3. Don't need the schema set up in advance.

Weaknesses of non-relational databases:
1. No joins tables, so you have to make multiple queries manually.
2. Many are open-source, so it can be harder to get technical support
3. Much more difficult to maintain

NoSQL was developed very recently in response to new and rapidly-changing
data types.

NoSQL helps apps remain "on" at all times and are adaptable to a variety
of devices.

NoSQL database types include:

Document database, which pairs keys with documents
Graph stores, which store info about networks of data
Key-Value Stores: Stored with names and values
Wide-column stores: Optimized for queries in larger databases. Different
in that they store columns instead of rows.

Schemas are dynamic instead of "fixed" at the beginning of development.

When SQL does "auto sharding" (horizontal partitioning of data). The data
can be spread across an arbitrary number of servers. If one server goes down,
it can be replaced without disruption.

Maybe I'm reading into this, but this reminds me a bit of hearing about
a person having a stroke and losing function in a limb, but then they
regain that function because another part of the brain takes over.

NoSQL keeps frequently used data in system memory, instead of caching. 
