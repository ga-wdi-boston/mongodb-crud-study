# mongodb Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

- [NoSQL Databases Explained](https://www.mongodb.com/nosql-explained)
- [Getting Started with MongoDB](https://docs.mongodb.org/getting-started/shell/)
- [Mongo DB Is Web Scale](https://www.youtube.com/watch?v=b2F-DItXtZs) (watch full video)
- [CodeSchool MongoDB](https://www.codeschool.com/courses/the-magical-marvels-of-mongodb) (Level 1)
- Install Mongodb by running `brew install mongodb` then to make sure you are up
to date run `brew update` then `brew upgrade mongo`.

## Advantages of MongoDB

In your own words, what are some advantages of a NoSQL database?

```md
A noSQL database can be started more quickly than a relational database.  In applications where relations are very minimal or non-existent, searching and caching is much faster with a non-relational db.  It is also better to use when data is constantly updating or changing.  Other reasons to use a non-relational db is because it allows data to be sharded, or separated onto different servers in different places.  This means more security because the likelihood of all the servers going down at the same time is minimal.
```

## Disadvantages of MongoDB

In your own words, what are some disadvantages of a NoSQL database?

```md
Some data has to be replicated no matter which type you use, but in general it seems that a noSQL will have more repeating data because it doesn't store references and allow access to the data through those references in the same way that a relational db does.
```

## Popularity

Why is MongoDB so popular?  Explain why popularity should not be the only factor
when choosing a technology

```md
Mongodb is popular because it aims to be simple.  You don't need to have a plan or a set long-term goal.  The data stored with an entity is all of the data that entity needs access to, and thus it is faster to query that set of data from the entity.

The long term goals of the app need to be considered.  It might save work (and therefore money) to start with the correct database for the project.  Or if a mongodb needs to be set up immediately, plans to migrate to a relational db (if needed) should be made earlier rather than later so that it takes less time and is easier.
```
