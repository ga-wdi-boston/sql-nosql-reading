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

NoSQL Database Types:

Document Databases:
  -key paired with document
  -document: key value pairs, key-array pairs, or nested docs
Graph Stores:
  -store info about networks of data
  -ex: social connections
Key Value Sotres:
  -simplest
  -key + value
Wide-column stores
  -optomized for queries over large datasets
  -store columns of data together instead of rows

NoSQL:
-non relational database
-more scalable superior performance
-addresses:
    -large volumes of rapidly changing semi structured unstructured data
    -frequent code pushes
    -flexible object orient programming
    -geographically disrributed
-allows insertion of data without predefined schema
-allows validation to be applied in database rather than application
-support auto-sharding
    -automatically spread data across number of servers
    -not require app to be aware of server pool
-integrated caching capabilities

MONGO DB example:

{
  sku: "00e8da9d",
  type: "Film",
  ...,
  asin: "B000P0J0AQ",

  shipping: { ... },

  pricing: { ... },

  details: {
    title: "The Matrix",
    director: [ "Andy Wachowski", "Larry Wachowski" ],
    writer: [ "Andy Wachowski", "Larry Wachowski" ],
    ...,
    aspect_ratio: "1.66:1"
  },
}

query:

qquery = db.products.find( { 'pricing.pct_savings': {'$gt': 25 })
query = query.sort([('pricing.pct_savings', -1)])

query = db.products.find({
    'type': 'Film',
    'title': {'$regex': '.*hacker.*', '$options':'i'}})
query = query.sort([('details.issue_date', -1)])


The $options operator specifies a case insensitive match.

Cache invalidation is just knowing when a piece of your cached data is out of date, and needs to be updated or replaced.
