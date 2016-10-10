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
Relational databases were not designed to cope with the scale and agility challenges that face modern applications, nor were they built to take advantage of the commodity storage and processing power available today.

When compared to relational databases, NoSQL databases are more scalable and provide superior performance,

NoSQL databases are built to allow the insertion of data without a predefined schema. That makes it easy to make significant application changes in real-time, without worrying about service interruptions

The best models use a single MongoDB collection to store all the product data, which is similar to the single table inheritance relational model. MongoDB’s dynamic schema means that each document need not conform to the same schema. As a result, the document for each product only needs to contain attributes relevant to that product.

MongoDB is a document-oriented database. Instead of storing your data in tables made out of individual rows, like a relational database does, it stores your data in collections made out of individual documents. In MongoDB, a document is a big JSON blob with no particular format or schema.

We could also model this data as a set of nested hashes. The set of information about a particular TV show is one big nested key/value data structure. Inside a TV show, there’s an array of seasons, each of which is also a hash. Within each season, an array of episodes, each of which is a hash, and so on. This is how MongoDB models the data. Each TV show is a document that contains all the information we need for one show.
