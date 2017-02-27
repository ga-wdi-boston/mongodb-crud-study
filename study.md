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
NoSQL databases can handle large amounts of structured, semi-structured and unstructured data.
They make it easy to perform simple queries like, "give me every Disney movie from the 80's", but that also means that the data must be consistent across the database.
There are no need for consistensy checks, because because the different rows are unrelated to each other. You can have a database distributed across many different machines that only have part of a table and because the nodes don't communicate with each other, there's no limit to the number that you can have.
This database offers great performance and large scalability.

```

## Disadvantages of MongoDB

In your own words, what are some disadvantages of a NoSQL database?

```md
There can be a lack of consistency and you are not able to make simple relational queries like you can do in SQL. You can only give the value with the index.
```

## Popularity

Why is MongoDB so popular?  Explain why popularity should not be the only factor
when choosing a technology

```md
"MongoDB is great for modeling many if the entities that back most modern web apps"

When it comes to choosing technology, there are many factors that need to be considered. Just because something may be fast or scalable does not mean it is the right choice for your requirements and choosing the wrong technology can cost more than what you thought it was saving.

source: https://blog.mlab.com/2012/08/why-is-mongodb-wildly-popular/
```
