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
They're super easy to both add and get data out of, and require no special language requirements (as opposed to SQL).  You can add additional data to MongoDB as it becomes needed, and it's stored in a programmer friendly format.
```

## Disadvantages of MongoDB

In your own words, what are some disadvantages of a NoSQL database?

```md
The data is not stored directly when you store it - that's something that immediately worries me.  It doesn't handle relations nearly as well as a relational database - to do so it winds up creating a lot of duplicate data.  The data that MongoDB stores, while easily searchable, is not uniformly organized.
```

## Popularity

Why is MongoDB so popular?  Explain why popularity should not be the only factor
when choosing a technology

```md
MongoDB is popular because it can grow and scale with a project.  Initially perhaps you only need a few bits of data stored, and MongoDB will let you change the amount and types of data you need to store as they come up.  However, just like anything with pros and cons, there is not one solution no matter how popular it may be.  Just because a tool is popular does not mean it's universally appropriate.
```
