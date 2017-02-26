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

1.NoSQL has many different database types including key-value stores, document databases, wide-column stores, and graph databases
2.NoSQL allow dynamic schemas, which means you can insert data into relational database without a predefined schema.
3.Most NoSQL databases can support automatic database replication to maintain database availability for outages or maintainance situations.

Use cases for non-relational databases:
  When there is a need to store serialized arrays in JSON objects;
  Storing records in the same collection that have different attributes;

Use cases for relational databases:
  When structure of your data has value (need a schema);
  Link information from different tables through use of foreign key (managing data transaction);
  Handle lots of complicated querying;

 Strengths of non-relational databases:
  It can incorporate any type of data(Flexible data model);
  All the Non-relational database tools support horizontal scaling;
  It allow insert data into database without a predefined schema;

 Strengths of relational databases:
  The objects in the relational databases are stricturely structured;
  Most of the tables are related to each other with primary and foreign keys thus providing “Referential Integrity” amoung the objects;
  All data written to the database are subject to the rules defined(Consistency);
