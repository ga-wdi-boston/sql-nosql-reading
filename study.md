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

Relational databases are store data in a way that's similar to spreadsheets - in
tables and rows, and allows you to link data from different tables through foreign
keys. This makes it suitable for applications that need to deal with intense data
analysis and transactions. However, it would not be ideal for applications that
have an enormous amount of data, because then the work can get tedious. Since the
database needs to know what you are storing in advance, each time you complete new
features, the schema of your database needs to change, making an application more
difficult and expensive to scale.

Non-relational databases, represent data in collections of documents (JSON, CSV
etc.), without structured mechanisms to link different documents of data together.
You do not have to predefine your schema like in relational databases, making it
more flexible and allowing for more frequent code pushes, and faster schema
iteration. However, precisely because of the unstructured-ness of non-relational
databases, it may cause headache depending on what kind of data you have. For instance,
if you're dealing with social data, where a lot of different documents are actually
very much related, it might result in data duplication, causing strange errors
and inconsistent data. If your data is relatively self-contained, using non-
relational databases would be a good choice, otherwise, it would be worth it to
consider relational databases.
