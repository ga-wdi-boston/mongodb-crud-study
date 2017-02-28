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
Some advantages of using a NoSQL database are you dont need a predefined schema
to store data as you do in a relational database, you can 'shard' your database
accross multiple servers which allows a more stable application (if one server
goes down you dont need to worry about the whole app crashing as other servers
can pick up the slack), potential for easy scalability, data unstructured, unchanging,
and is easy to setup and maintain.
```

## Disadvantages of MongoDB

In your own words, what are some disadvantages of a NoSQL database?

```md
Some disadvantages of a NoSQL database are that while it is easy to setup and maintain
due to its loose structure as the app evolves one may have to move to relational
database which can be difficult once a lot of data is generated and no join tables
so making relationships between data can be difficult.
```

## Popularity

Why is MongoDB so popular?  Explain why popularity should not be the only factor
when choosing a technology

```md
MongoDB is so popular because it is inexpensive to setup and maintain. Unlike a
relational database which required more planning to setup the relationships between
the tables, minimal planning is required in order to setup a non-relational
database. Popularity should not be the only factor when choosing a technology,
one should look at the needs of the application and database they are building
and choose the database structure that best suits their needs.
```
