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

Relational databases are the better choice when you know what type of data you
will be storing and your schema will not change frequently. Non-relational databases
are ideal when a quick development cycle is required and you must store data
without yet having a locked-down schema in place. Situations in which a relational database
would require many joins can sometimes benefit from using a non-relational database,
but be sure your data is not representing one thing in many places as that can
be a slippery slope.

### Strengths of Relational Databases

1. Represent relational data without duplicating data
2. More established technology as they have been around longer
3. When combined with a cache, speed can rival NoSQL as well as offer more stability

### Strengths of Non-Relational Databases

1. More easily scalable using more servers
2. Different NoSQL databases offer different datatypes (document, graph, etc) which can be well-suited to certain applications
3. Suited to quick development cycles as you don't need to know what you are storing in advance
