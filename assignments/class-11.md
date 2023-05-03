# Class 11: Reading Questions

- Five differences between SQL and NoSQL databases: 

| Aspect            | SQL                                                          | NoSQL                                                        |
| ----------------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| Data Model        | Relational                                                   | Non-relational (document, key-value, column-family, graph)   |
| Schema            | Fixed and pre-defined                                        | Dynamic and schema-less                                      |
| Scalability       | Vertical (scale-up)<br /> Adding more resources to a single server. | Horizontal (scale-out)<br /> Involves adding more servers to a system. |
| Query Language    | Structured Query Language (SQL)                              | Various (depending on the database)                          |
| Consistency Model | ACID (Atomicity, Consistency, Isolation, Durability)         | BASE (Basically Avaialble, Soft-state, Eventually consistent) |



- What kind of data is a good fit for an SQL database?

Structured data and well-defined relationships as well as a fixed schema. This includes data that can be organized into tables with rows and columns. SQL databases excel at handling complex queeries and transactions in a consistent and reliable manner. 

- Give a real world example.

  Customer information, financial records, or product inventory.

- What kind of data is a good fit a NoSQL database?

Unstructured or semi-structured data with flexible or evolving schema requirements. 

- Give a real world example.

For examplee, media posts, sensor data from IoT devices, or multimedia content. 

- Which type of database is best for hierarchical data storage?

NoSQL databases, specifically graph or document-oriented databases, are typically better suuited. These databases can efficiently represent and query nested, interconnected data structures, making them an excellent choice for handling hierarchical data. 

- Which type of database is best for scalability?

NoSQL databases are considered better for scalability as they are designed to handle large volumes of data and can easily distribute data across multiple servers, enabling horizontal scalability. 

- What does SQL stand for? 

SQL stands for structured query language, a programming language used to communicate with and manage relational databases. 

- What is a relational database? 

A relational database is a type of database that organizes data into tables with rows and columns, where each row represents an entity and each column represents an attribute of that entity. Relationships between entities are desined using keys, allowing for efficient querying and data retrieval. 

- What type of structure does a relational database work with? 

A relational database works with a tabular structure, organizing data into tables with rows and columns, and defining relatioonships between these tables using keys. 

- What is a ‘schema’? 

A schema is a blueprint for the structure of a database, defining the tables, their columns, data types, and the relationships between tables. 

- What is a NoSQL database? How does it work? 

A NoSQL database is a non-relational database designed for handling unstructured or semi-structured data, offering flexibility in data storage and scalability across multiple servers. 

It works by storing data in various formats such as key-value, document, Coolum-family, or graph, depending on the database type. 

- What is inside of a MongoDB database? 

Inside a MongoDB database, data is stored as documents in a format called BSON, which is a binary-encoded serialization of JSON. These documents are organized into collections, which are analogous to tables in relational databases. 

- Which is more flexible - SQL or MongoDB? and why. 

MongoDB is more flexible than SQL databases because it does not require a fixed schema, allowing for dynamic changes in data structures without the need to modify the entire database. This makes it easier to adapt to evolving data requirements. 

- What is the disadvantage of a NoSQL database?

The main disadvantage is the lack of support for complex transactions and consistency guarantees that are typically offered by SQL databases. This can make NoSQL databases less suitable for situations where data consistency and integrity are crucial, such as financial transactions or inventory management. 