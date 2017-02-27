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
- There are many different situations where relational or non-relational
  databases are appropriate. Such cases depend on the scalability of the
  database. NoSql uses non-relational databases, this means that they can
  provide more performance because there's no need to provide information about
  the relationships. The Use Cases here are Operational Intelligence, Product
  Data Management, and Content Management Systems. For the Operational
  Intelligence we have to look at data collected by logging systems, application
  output, and other systems. Here, we don't need to use a relational database
  because we aren't logging the relationships between the data. But thre could
  relational data between the different outputs. For the Product Data
  Management, we will be looking at managing inventory in e-commerce and
  building product catalogs. We can use non-relational databases because
  catalogs don't need to know the existing inventory, and instead provide what
  could be expected. However, because as humans we can see the relationship
  between the inventory and catalogs, we would use a relational database to keep
  the catalogue up-to-date with the inventory.

- Three strengths of relational databases:
  1. Works with structured data.
  2. Built-in Data integrity.
  3. Index without any limits.

- Three strengths of non-relational databases:
  1. Can use any type of data, including rich data types.
  2. Scale the database as the audience grows.
  3. Projects cost 10% less.
