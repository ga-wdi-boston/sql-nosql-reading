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
Relational databases are appropriate when needs can be simplified - data in/data
out, with some functionality to join data when needed. They are useful when your
data are static and you don't forsee the need to change the structure of it once
it's been built. They also cannot contain all data types (mostly just text). An
example of a relational database may be at a health center where data are collected
for patients in the form of text.
In contrast, non-relational databases allow for flexibility in a changing
environment. They are cheaper to maintain and work with, and allow for any data
type to be stored and manipulated, in the context of documents (all data
for a given record is in one document, rather than spread across different
tables like in a relational database). An example of a
non-relational database use is in inventory management. Here, consumers use
electronic shopping carts to buy goods. Non-relational databases allow for
many changes to occur within the context of a shopping cart - changing behaviors
of the consumers, changes in inventory/product availability, price changes, etc.
They allow for the flexibility that occurs in everyday commerce.
