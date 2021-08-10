# NoSQL

## What is NoSQL?

NoSQL refers to non-relational databases, also known as “**not only SQL**”, is a database design method that allows you to store and query data outside of the traditional relational database structure. By using this we can more easily manage and develop many different forms of data structures. NoSQL databases are generally best for storing and modelling structured, semi-structured, and unstructured data in one database. Some of the common NoSQL databases include MongoDB, Apache Cassandra, Google Cloud BigTable, Apache HBase, and Redis.

## Pros of NoSQL

- Flexible
- High performance
- Highly functional
- Scalable

## Types of NoSQL

### 1. Document databases

The document database is a non-relational database designed to store and query data in the form of JSON-like documents.

> Due to its flexibility, the document database is very suitable for collecting and storing any type of data.

```
[
    {
        "Name" : "Harshdeep Singh",
        "Age"  : 20,
        "Contact info" : {
            "Mobile_number" : 0123456789,
            "email_id"      : "random@gmail.com"
        }
    }
]
```

### 2. Key-value databases

A key-value database stores data as a set of key-value pairs, where key is a unique identifier. Both keys and values ​​can be anything from simple objects to complex compound objects.

> The key-value database provides high-speed memory access for handling many small, continuous reads and writes.

### 3. Wide-column stores

The wide-column store uses the modified table model to process data. It uses key rows that can be mapped to one or more dynamic columns to store data. These rows are flexible and column data can vary from row to row. Wide column store is used to store large amounts of data.

> It is used when you need a large data set, especially if the columns of all rows are not always the same.

### 4. Graph databases

Graph databases use nodes to store data entities and edges to store relationships between entities. There is no limit to the number and types of relationships a node can have.

> Graph databases are used for highly interconnected data. The simplest use case for graph databases is social media.

## Choosing NoSQL over SQL

> - NoSQL is faster than SQL.
> - NoSQL database has a flexible data model.
> - Easy for developers to work with.
> - It is designed for storing and analyzing structured, semi-structured and unstructured data in one database.

## References

* [NoSQL MongoDB](https://www.mongodb.com/nosql-explained)
* [SQL vs NoSQL](https://www.imaginarycloud.com/blog/sql-vs-nosql/)
* [NoSQL Amazon](https://aws.amazon.com/nosql/)
* [NoSQL tutorial](https://www.guru99.com/nosql-tutorial.html)
