# Relational and Non-relational Databases Study

Read the following articles thoroughly. Practice active reading by taking notes.

-   [NoSQL Databases Explained | MongoDB](https://www.mongodb.com/nosql-explained)
-   [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/) (click
    through to at least one detailed example)
-   [Why You Sould Never Use MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/)

As you read, pay special attention to addressing the following:

-   Identify use cases where relational or non-relational databases are
    appropriate.
Use Cases for non-relational databases:
1. For log data from servers and other machine data - database is used as a persistent storage engine
2. For collecting a processing events in real time for use in generating up to the minute or second reports
3. For Product Catalog - must have the capacity to store many different types of objects with diffent sets of attributes.
4. Category Hierarchy - product category herarchy for E-commerce
5. Metadata and Asset Management - using CMS and Mongo to store the content of my site
6. Storing Comments - 3 patterns - store in its own document, in parent document,
stores comments separately from the parent but aggregates comments into a small number of documents

Use Cases for relational databases:
1. Hierarchical Aggregation - If needed to have access to aggregated data in a usable form
2. Inventory Management - shopping cart activities at e-commerce store - the cart ages

List three strengths of relational databases.
1.The relational database model eliminates duplicate data
2. allows easy access to information.
3. It also makes it easier to update data.

List three strengths of non-relational databases.
1. Large volumes of changin data in all kinds of types - structured, semi-structured,
unstructured
2. Agile sprints - frequent code pushes
3. Uses object oriented programming - easy to use and flexible
4. Scale-lout architecture distributed

After you've finished your study, summarize your notes to the following section
and open a pull request.

Be prepared to share your notes with others before the discussion. Everyone
should have something to contribute.

## Summary

<!-- your notes here -->
Relational databases are not prepared for the scale and agility challenges
which modern applications need to tackle, also they don't process power available
today as well ass they don't use commodity storage to their advantage.

MongoDB is the leading non-relational database - NoSQL Database. This setup takes care of everything
- performance, high availability, security, disaster recovery.
several types:
document databases - each key is pair with a document
graph stores - store information about networks of data, such as social connetions.
key-value stores - are the simplest NoSQL databases. Every single item is stored
as an attribute name together with its value.
wide-column stores - store columns of data together, isntead of rows

Benefits of NoSQL Databases:
1. Large volumes of changin data in all kinds of types - structured, semi-structured,
unstructured
2. Agile sprints - frequent code pushes
3. Uses object oriented programming - easy to use and flexible
4. Scale-lout architecture distributed
