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

noSQL is object/document oriented database instead of the relational oriented
database like mySQL and Postgres. It involved two columns only instead of rows
and columns which gets turned into tables. Each object in noSQL gets its own document
and each document becomes part of the collection. Instead of schemas which require
migrations and taking the database offline, to update/add information onto the database
it does not require the databse to be taken offline but instead can just add the
new information to the collection without distrupting the database. noSQL databases
also have the capability to communicate with several different servers instead of one.
mySQL databsase can also communicate with more than one server potentially,
however doing so would require more grunt work.


Using mongoDb as a replacement for mySQL or other relational databases is not a
good idea. Since mySQL has joined tables created and being able to reference other
tables without creating duplicates this would become a nightmare for deaing with
mongo. The team would have to go by one by one and handle each duplicate case. The
mongo architecture is good when it comes to sending and recieving data from an api
from the user.

<!-- your notes here -->
