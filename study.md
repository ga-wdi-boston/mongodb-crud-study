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

Large volumes of rapidly changing structured, semi-structured, and unstructured data

Agile sprints, quick schema iteration, and frequent code pushes

Object-oriented programming that is easy to use and flexible

Geographically distributed scale-out architecture instead of expensive, monolithic architecture

```

## Disadvantages of MongoDB

In your own words, what are some disadvantages of a NoSQL database?

```md


when your write to mongodb you dont write anything you stage the data to be written on later time
if theres a proroblem writing data youll have issue
```

## Popularity

Why is MongoDB so popular?  Explain why popularity should not be the only factor
when choosing a technology

```md

Asynchronous insert and update: What it means is MongoDB doesn't insert data to DB as soon as insert query is processed. Same is true for updates.

No Joins overhead: When they say MongoDB is a document database, what they mean is a database that contains data that is self sufficient and all the information is embedded like a real document.
```
