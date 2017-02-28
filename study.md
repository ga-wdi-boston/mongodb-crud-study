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
A NoSQL database is a non-relational database.  Some advantages it has are: it is more scalable and generally has higher performance than relational databases.  It is more adaptable and can deal with frequent code changes easily.  Server load is balanced over a large number of servers, so if one server goes down it has minimal effect.  It has quick access to the information because everything is stored in a json string; there are no foreign keys.
```

## Disadvantages of MongoDB

In your own words, what are some disadvantages of a NoSQL database?

```md
Non-relational databases aren't as consistent as relational databases.  If data becomes lost or corrupt, they cannot just 'nuke-pave' and reset the datbase because it is a cache without a backup.  It is also difficult to add relationships between data in a non-relational database.
```

## Popularity

Why is MongoDB so popular?  Explain why popularity should not be the only factor
when choosing a technology

```md
It is so popular because it makes it easy to get a responsive database up and runnning quickly.  One should consider if MongoDB is appropriate for their type of data storage first, because using a relational database may suit them better.  
```
