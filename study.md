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

QUESTION ONE: Identify use cases where relational or non-relational
databases are appropriate.
Relational databases like SQL work well in situations where:
  -The data-types and schema are known and easily defined when the
  database is created (at the outset)
  -An example might be in health-care, where patient record data would
  fit this model - we would know at the outset what types of data we want
  to collect, so there would not be a frequent need to change the structure of
  the DB
Non-relational databases work well in situations where:
  -We need more flexibility, because data might be changing rapidly
  -An example would be the inventory at an e-commerce site

QUESTION 2: List three strengths of relational databases.
  1. Relational databases limit redundancy/duplication of data. This is because
  all the data pertaining to a particular object is stored together,
  then linked to related objects, eliminating the need to store data about
  the original object in multiple places.
  2. Relational databases avoid data inconsistencies. This is because they use
  a simple table structure that stores the data in one place, so when data needs
  to be updated, it only needs to be updated in that one place. This reduces the
  likelihood that errors will arise from a need to update data in multiple places
  3. This is just my own opinion, I did not come across it in my reading, but it
  seems to me that relational databases are the more traditional, and maybe even
  "old-school" choice, and this makes them reliable and predictable,
  because of the sheer fact that they've been around longer, and therefore have
  been tested more.

QUESTION 3: List three strengths of non-relational databases.
  1. Non-relational databases allow for greater flexibility with data - as such,
  they are often better at representing "real-world" entities and their
  complex relationships.
  2. Non-relational databases allow companies to scale more quickly than
  with traditional relational DBs.
  3. Non-relational databased are cheaper to maintain, because they don't
  require the same kind of maintenance as traditional DBs when data
  structure changes (ie, because of the enhanced flexiblity).
