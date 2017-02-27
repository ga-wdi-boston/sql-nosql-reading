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
3 strengths of non-relational databases:
1. Storing and retrieving data
2. Great for caching and retrieving data.
3. Doesn't care about the shape of the data


3 strengths of relational databases:
1. Easy access to tons of related data.
2. Can be done in real time
3. Easy to cross-reference information

This seems obvious, but when the data is actually non-relational a non-relational database is a good idea. Generally, when handling large amounts of data, non-relational databases are more effective. My understanding is that relational databases are generally more common but the use of non-relational databases is for a larger scale. 


Here are my takeaways from these readings:
1. NoSql is a category of database management systems.
2. Its main characteristic is its non-adherence to relational database concepts.
3. NoSQL means "not only sql"
4. A relational databse for massive volumes of data can give a very slow response time, which causes a problem for large comapnies with large databases (like Amazon, Facebook, Etc...)
5. To solve the above problem, we can distribute the database load on multiple hosts as the load increases. This is called "Scaling out". "Horizontal scalability" - you keep on adding more computers as you need more power. Performance is linearally proportional to the number of computers you have.
6. NoSql databases are non relational databases that scale out better than relational databses.
7. NoSql databases do not use SQL to query data or use strict schemas, like relational models.
8. This means that some good features of SQL are not always guaranteed.
9. NoSQL databases are highly specialized Systems with limitations. It is better for handling huge volumes of data.
10. The majority use relational data.
Other notes on noSQL:
11. In a relational database, we have to know what the structure (or schema) of the database is before we write data into it. The structure gives us context.
12. NoSQL allows you to apply a structure to a data but doesn't require it up front. You can store data even if you don't have the logical strucutre (category) for it yet.
MongoDB:
1. Its a noSQL database. It's an open source Document database to be specific. Data or records are stored as documents.
2. They use JSON-like syntax.
3. You should plan out the structure of your database and collections, but you don't have to do any pre-defined structuring before you build your application.
4. Scaling is one of the big advantages to mongoDb (and noSQL databases in general). They are easy to scale compared to SQL or relational databases.
5. They are faster in most operations.
6. We have a collection in Mongo rather than a table for SQL.
7. You can dump data in and retrieve it out based on its unique identifier (key).
8. There are no relations between the data unless they are parent-child
9.
