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

NoSQL
- Different database technologies that were developed to meet demands:
    - Changing data types
    - Speed
    - More accessibility
Types:
- Document databases
    - Pair each key with a document… documents can have a bunch of key-value pairs, key-array pairs, nested documents
- Graph stores
    - Store info about networks of data
- Key-value stores
    - Each item in the database is stored as a key with a value
- Wide-column stores
    - Store columns of data together instead of rows
Pros
- Can handle larger amounts of structured, semi-structured, and unstructured data
- Faster
- Easier to use
- Geographically distributed scale-out architecture… not 100% sure what this means… does it work more broadly ? Does this have to do with the auto-sharding?
- More flexibility with schemas… can insert data without predefining your schema… makes things faster

Scaling vertically means one server has to host an entire database to ensure acceptable performance
- Pricey
Scale horizontally? Add servers instead of putting everything on one server aka sharding

MongoDB pros:
- Flexible schema, good for storing info for data management
Cons:
- Difficult if you have different types
