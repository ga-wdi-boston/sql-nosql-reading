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

SQL NoSQL
document based db - docs are json blobs

Relational databases were not designed to cope with the scale and agility challenges that face modern applications, nor were they built to take advantage of the commodity storage and processing power available today.

benefits of non-relational db
* Large volumes of rapidly changing structured, semi-structured, and unstructured data 
* Agile sprints, quick schema iteration, and frequent code pushes 
* Object-oriented programming that is easy to use and flexible 
* Geographically distributed scale-out architecture instead of expensive, monolithic architecture

drawbacks of mongo
graph db too niche to be put in production
decentralized so updating and deleting is error-prone
no join feature - cannot relate related data

strengths of relational db
in production
simple
by name, can store related data






Storing Log Data MONGO

event fed servers store logs like http reqs
sql stores log
mongo puts each section of the log into a doc
ie. what page, user, req - can omit data

sync and synch write concerns

queries by file, date, host day+page
db max -> sharding  (shard by key)

data growth
capped db - sheds old data
multi capped - sheds a capped collection
