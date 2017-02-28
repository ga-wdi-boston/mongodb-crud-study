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
high performance, automatic scaling, handles large data easily, no need joins, no need
to set specifications, stores any file withou complicating the stack, great for
unstructured date, doesn't have a query language like SQL
```

## Disadvantages of MongoDB

In your own words, what are some disadvantages of a NoSQL database?

```md
Mongo doesn't error when duplicate ID appears so we have to have data right in the first
place.
No support for transactions - a certain atomic operations are supported at a single document level. 
Less up to date information available - fast evolving product
```

## Popularity

Why is MongoDB so popular?  Explain why popularity should not be the only factor
when choosing a technology

```md
MongoDB is a very popular because it allows to build a database very quickly which
means to present some prototype to investores in the start up in a reasonable time
befofe the compatition kicks in with some similar idea. Also for data of a small
company it's viable to user MongoDB as well. Runs itself, easy to maintain. But if
we need a stable secure database and more structured data, then better to run database
through relational language as SQL.
```
