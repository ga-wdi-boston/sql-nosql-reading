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

<!-- your notes here -->
Summary:
     MongoDB was created to better fit the current work practices of development teams, and to help businesses save some money and resources.  It allows developers to efficiently make changes to / update their databases without sacrificing performance or needing downtime (downtime may result in monetary losses for businesses).  It is useful for businesses that have large sets of data that are constantly changing.  Since a predefined schema isn’t required, adding columns and changing the data is easier.  Autosharding allows the database to be split across multiple servers without the manual labor that relational databases would require.  However, one of the downsides of this is that the benefits of relational databases, such as transactional integrity, is compromised.

Use cases for non-relational databases:
* Product data management - store inventories, product catalogs
* Storing log data, machine generated data
* Content management systems

Use cases for relational databases:
* When structure of your data has value (need a schema)
* When your data needs to be connected in someway, linked together
* If the structure of your data won't be changing much

Strengths of non-relational databases:
* Allows for changes / updates to be made without having to turn off servers
* Handles large volumes of constantly changing data
* Scaled out across multiple servers, thus making it cheaper to maintain than having it all in one place

Strengths of relational databases:
* Ability to use join tables, MongoDB joins need to be done manually and can get messy
* Allows data to be consistent
* Transactions maintain ACID properties that ensure accuracy, completeness, and data integrity
