# Database Management Systems 

This repository contains the curriculum, syllabus, and practical experiments for the Database Management Systems course offered in Semester 4. The course emphasizes both the conceptual foundations and hands-on implementation of database systems using MySQL. It broadly covers database architecture, ER modeling, the relational model, SQL, normalization, transactions, concurrency control, indexing, query optimization, and storage mechanisms.

## Course Outcomes

| Outcome | Description | Bloom's Level |
| :--- | :--- | :--- |
| **CO1** | Explain DBMS architecture, ER modeling, relational model concepts, and ER-to-relational mapping. | 2 |
| **CO2** | Construct and manipulate databases using SQL including DDL, DML, joins, and subqueries. | 3 |
| **CO3** | Develop advanced SQL solutions using views, CTEs, stored procedures, and triggers. | 4 |
| **CO4** | Analyze functional dependencies, perform normalization, and evaluate transaction and concurrency mechanisms. | 4 |
| **CO5** | Evaluate indexing strategies, query optimization techniques, and storage mechanisms for performance tuning. | 5 |

## Syllabus & Practicals Overview

| Unit / Focus | Topics Covered | Key Practicals |
| :--- | :--- | :--- |
| **Unit I: Fundamentals** | DBMS vs file systems, three-schema architecture, ER concepts, relational algebra, and mapping. | Design an E-commerce ER diagram and convert it into a relational MySQL schema with constraints (Exp 1 & 2). |
| **Unit II: SQL Basics** | DDL, DML, filtering, aggregates, GROUP BY, and various joins. | Create an Employee schema and execute queries using joins, aggregates, and EXPLAIN plans (Exp 3 & 4). |
| **Unit III: Advanced SQL** | Subqueries, CTEs, views, stored procedures, and triggers. | Implement recursive CTEs, updatable views, stored procedures, and triggers with error handling (Exp 5 & 6). |
| **Unit IV: Normalization & ACID** | Functional dependencies, 1NF to BCNF, transaction management, locking, and recovery mechanisms. | Normalize a denormalized table to BCNF and simulate banking transactions with isolation levels (Exp 7 & 8). |
| **Unit V: Optimization** | Indexing, B+ trees, EXPLAIN analysis, cost-based optimization, and InnoDB storage architecture. | Benchmark query performance using indexes and optimize slow queries on 10,000+ row datasets (Exp 9 & 10). |

## Reference Materials

* *Fundamentals of Database Systems* by R. Elmasri & S. B. Navathe (Pearson).
* *Database Management Systems* by R. Ramakrishnan & J. Gehrke (McGraw-Hill).
* *An Introduction to Database Systems* by C. J. Date (Pearson).
* *Database Systems: The Complete Book* by H. Garcia-Molina, J. D. Ullman, & J. Widom (Pearson).
