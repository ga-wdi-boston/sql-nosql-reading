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

Non-relational databases are helpful when it comes to:
 - Dealing w/ massive volumes of new, rapidly changing data types
 - Need to iterate through development cycles quickly; superior performance
 - Scale applications over time

 Example use cases:
  - Storing log data
  - Pre-aggregated reports
  - Product catalog
  - Inventory management

 There exists a number of different database types:
  - Document databases
  - Graph stores
  - Key-value stores
  - Wide-column stores


Strengths of non-relational databases:
  - Dynamic Schemas: built to allow the insertion of data without a predefined schema
  - Auto-sharding: natively and automatically spread data across an arbitrary number of servers
      Can scale horizontally minimizing costs and scalability issues
  - Integrated caching capabilities: keeping frequently-used data in system
    memory as much as possible and removing the need for a separate caching layer

Strengths of relational databases:
  - Proficient in handling data that is structured and known in advance
  - Limit redundancy or duplication of data
  - Data inconsistencies are avoided
