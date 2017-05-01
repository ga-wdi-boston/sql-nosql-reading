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

## Identify use cases where relational or non-relational databases are appropriate:

    #relational databases are better when the relationships of the data is important.
    like social network apps, storing comments etc
    and when small-medium amounts of data where every column is known in advance.

    #Non-relational databases are better when rapidly changing data types
    and accessible form many devices

## List three strengths of relational databases:

    Have join tables to make cleaner relationships (if the relationships are clean to start with).

    Data is less likely to become inconsistent because if something is updated, it only needs to be updated in one place (its row) due to all links being done by ids, foreign keys and join tables.

    Stores data in tables


## List three strengths of non-relational databases:

    It allow insert data into database without a predefined schema

    Can handle large amount of data without using a lot of disk space.

    Handle unstructured and semi-structured data - allows for more flexibile schema and datatypes.
