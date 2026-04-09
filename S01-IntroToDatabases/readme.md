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

---

2. NoSQL Databases: These databases are designed for unstructured data and do not use the traditional table-based structure. Examples include MongoDB, Cassandra, and Redis.
