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

- Relational databases are appropriate

    - with structured data
    - when your data need to be linked together, e.g. in a social networking site
    - when You’re building a low-volume, medium-complexity suite of applications that will evolve over time.

- non-relational are appropriate

    - with unstructured or unknown data
    - when there’s a large database
    - with rapidly changing structured data
    - with Object-oriented programming.

- List three strengths of relational databases.
    - transactional integrity
    - reliable
    - stable

- List three strengths of non-relational databases.
    - they are more scalable than relational database
    - support automatic database replication to maintain availability in the event of outages or planned maintenance events
    -  have excellent integrated caching capabilities


A SQL database needs to know what you are storing in advance. It scales vertically, which means that a single server has to host the entire database to ensure acceptable performance for cross- table joins and transactions. This action causes limits on scales. noSQL, on the other hand, scales horizontally. It adds servers instead of concentrating more capacity in a single server. Some NoSQL database types includes document databases, graph stores, key-values stores, and wide-column stores.

MongoDB is a document-oriented database. Instead of storing your data in tables made out of individual rows, like a relational database does, it stores your data incollections made out of individualdocuments. In MongoDB, a document is a big JSON blob with no particular format or schema. The only thing it’s good at is storing arbitrary pieces of JSON, which you means that you don’t care at all what’s inside that JSON.
