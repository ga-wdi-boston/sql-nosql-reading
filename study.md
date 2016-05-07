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

Use cases for relational databases:

-   Small or medium sized websites where data doesn't have to be spread across
multiple servers
-   Corporate data where is frequently referenced across multiple tables
-   When data requires substantial links between documents to be properly
represented

Use cases for non-relational databases:

-   Storing log data (server or machine generated data that would be difficult
for humans to read/analyze without it being properly stored/aggregated)
-   Storing product/inventory data for e-commerce sites
-   Managing user generated content on a website (such as comments)
-   Storing data when the data is perfectly self-contained and doesn't require
references to other documents within the database

Strengths of relational databases:

-   They've been in existence since the 1970's so a wider range of developers
are familiar with them and understand their functionality
-   They are scalable (ie in the case of a company they can grow as the
company grows)
-   They limited redundancy or unnecessary duplication of data

Strengths of non-relational databases:

-   Takes large amounts of various data structures
-   Schemas don't have to be defined prior to adding data
-   Allows for agile development if the data structure needs to change and
avoids large/slow migrations
