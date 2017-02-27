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
MongoDB is web scale. That is to say, MongoDB retrieves data quickly, and is flexible. MongoDB also supports queries across a large number of documents. It is also highly scalable
```

## Disadvantages of MongoDB

In your own words, what are some disadvantages of a NoSQL database?

```md
MongoDB is web scale. That is to say, it has to make a number of sacrifices in order to gain the speed an flexibility which it touts. Chief among these is the fact that it will tell you it has written a document when in fact all it did was stage the change to be written at a later date, and if that fails, you will not know. Also, it does not handle siutations involving a large number of relationships between documents very well.
```

## Popularity

Why is MongoDB so popular?  Explain why popularity should not be the only factor
when choosing a technology

```md
MongoDB is web scale. That is to say it has a very good marketing team and rode a wave of noSQL popularity. It is also very good for rapidly prototyping a product.

Popularity should not be the only factor because people love to recommend their favorite things with zero consideration for the actual needs of an app.
```
