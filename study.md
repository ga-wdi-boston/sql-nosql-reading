# Relational and Non-relational Databases Study

Read the following articles thoroughly. Practice active reading by taking notes.

-   [NoSQL Databases Explained | MongoDB](https://www.mongodb.com/nosql-explained)
-   [MongoDB Use Cases](http://docs.mongodb.org/ecosystem/use-cases/) (click
    through to at least one detailed example)
-   [Why You Should Never Use MongoDB](http://www.sarahmei.com/blog/2013/11/11/why-you-should-never-use-mongodb/)

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

  - Using non-relational databases has many advantages over traditional SQL dbs.
    - Less downtime
    - More reponsive to schema changes
    - Spread data natively to an arbitrary number of servers to protect data
    - Supports integrated caching, a complex way of eliminating the need to constantly read from the DB
      - Allows commonly used data to stay in memory


  - Several excellent use cases for mongoDB
    - Operational intelligence
      - concerns the way that the server logs and stores its data
    - Product data management
      - concerns the way that companies can manage ecommerce sites
    - Content management systems
      - concerns the way that websites store their data like comments and info

    - One important use-case for mongoDB is inventory management systems
      - Maintains traditional shopping cart metaphor.
      - Goods in a stagnant shopping cart time out and return to active inventory

  - Why you should never use MongoDB
    - Diaspora's servers are split into pods
    - Each pod doesn't require access to the entire database.
    - When users on different pods interact, their respective pods are updated accordingly.
    - Still a rails app!  Uses mongoDB though.
    - Ran into some issues, started using relations
      - Realized this was now a relational database
      - Outgrew mongoDB
    - TV show program was good for mongoDB until client wanted it updated
      - Client wanted relations added
      - De-duped "actors"
      - Eventually needed a migration to PSQL

Moral seems to be to understand the scope of a project and what the project MIGHT turn into before deciding on data store.
