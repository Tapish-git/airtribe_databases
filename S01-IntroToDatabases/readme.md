#### What are databases?

A database is a structured collection of data that is stored and accessed electronically. It allows for efficient storage, retrieval, and management of data. Databases are used in various applications, such as websites, applications, and business systems, to store and organize information.

# What type of Databases?

There are several types of databases, including:

1. Relational Databases: These databases organize data into tables with rows and columns. Examples include MySQL, PostgreSQL, and Oracle. Basically there is some relation between data, for example, in a database of a school, there may be a table for students and another table for courses. The student table may have a column for the course ID, which can be used to link the two tables together.

**_The most important point for Relational databases is that they all follow ACID properties._**

### ACID stands for Atomicity, Consistency, Isolation, and Durability. These properties ensure that database transactions are processed reliably and that the integrity of the data is maintained.

Atomicity: This property ensures that a transaction is treated as a single unit of work. Either all operations within the transaction are completed successfully, or none of them are. If any part of the transaction fails, the entire transaction is rolled back, and the database remains unchanged.

Consistency: This property ensures that a transaction brings the database from one valid state to another valid state. It ensures that any data written to the database must be valid according to all defined rules, including constraints, cascades, and triggers.

Isolation: This property ensures that concurrent transactions do not interfere with each other. Each transaction should be isolated from others, meaning that the intermediate state of a transaction should not be visible to other transactions until it is completed.

Durability: This property ensures that once a transaction has been committed, it will remain so, even in the event of a system failure. The changes made by the transaction are permanently stored in the database and will not be lost.

---------------------

2. NoSQL Databases: These databases are designed for unstructured data and do not use the traditional table-based structure. Examples include MongoDB, Cassandra, and Redis.

-----------------------

3. Graph Databases: These databases are designed to represent and store data in the form of graphs, with nodes representing entities and edges representing relationships. Examples include Neo4j and Amazon Neptune.

-----------------------

Difference between SQL and NoSQL databases:
| Feature             | SQL Databases                 | NoSQL Databases              |
|---------------------|-------------------------------|------------------------------|
| Data Model          | Relational (tables)           | Various (document, key-value, graph)--|
| Schema              | Fixed schema                  | Dynamic schema               |
| Scalability         | Vertical Scaling (scale-up)   | Horizontal Scaling (scale-out) |
| Query Language      | SQL                           | Varies (e.g., MongoDB uses BSON) |
| ACID Compliance     | Yes                           | Varies (some NoSQL databases may not fully support ACID) |
| Use Cases           | Complex Queries, Transactions | Big Data, Real-time Web Apps, Flexible Schema |
-----------------------

#### Why do we need databases?
Databases are essential for managing and organizing large amounts of data efficiently. They provide a structured way to store, retrieve, and manipulate data, which is crucial for various applications and industries.

#### What is SQL?
SQL (Structured Query Language) is a programming language used to manage and manipulate relational databases. It allows users to create, read, update, and delete data in a database. SQL is widely used for querying and managing data in relational database management systems (RDBMS).

#### What is a DBMS?
A DBMS (Database Management System) is software that provides an interface for users to interact with databases. It allows users to create, manage, and manipulate databases, as well as perform various operations such as querying, updating, and administering the database. Examples of DBMS include MySQL, PostgreSQL, Oracle, and MongoDB.


