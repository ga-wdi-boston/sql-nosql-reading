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

Relational databases are really good for:
  small-medium amounts of data where every column is known in advance.
  (employer/employee/company)
  (books/authors/reviews)
Rdbs stay consistent, have been around since the 1970s (stable), and force
a dev to plan out a schema before starting to code

NRdbs are really good for:
large amounts of data that may have changing column information.
(tv show database in sarahmei's example)
(event logging)
(product catalogs)
NRdbs are easier to scale, allow for new "column" adds without taking the db
down (although they're not in column form), allow for unstructured data to be
saved. 
