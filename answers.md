<h3> Database Design & Programming with SQL  WEEK 1 ASSIGNMENT</h3>

<h4> 1. State and Explain the components of a DBMS(Database Management System) </h4>
<li> Database Engine: Core component that manages data storage, retrieval, and updating operations. </li>
<li>  Database Schema: Defines the structure of the database, including tables, views, indexes, and relationships. </li>
<li> Query Processor: Interprets and executes database queries, converting them into low-level instructions. </li>
<li>  Transaction Manager: Ensures that database transactions are processed reliably and adhere to ACID properties (Atomicity, Consistency, Isolation, Durability). </li>
<li>  Storage Manager: Manages the physical storage of data, including file management, indexing, and data retrieval. </li>
<li>  Data Dictionary: Stores metadata about the database, such as schema, tables, columns, and constraints. </li>
<li>  User Interface: Provides tools for users (e.g., SQL interface, graphical tools) to interact with the database. </li>

<h4> 2.What is a relational database? Give 4 examples. </h4>
A relational database is a type of database that stores data in tables (relations), where each table consists of rows and columns. Data in a relational database is organized into relationships based on common attributes, using keys to link tables together.
Examples of Relational Databases:
MySQL
PostgreSQL
Microsoft SQL Server
Oracle Database

<h4> 3. State and Explain three classifications of SQL? </h4>
SQL (Structured Query Language) is classified into three main types:

* Data Definition Language (DDL):

Purpose: Defines the structure of the database.
Commands:
CREATE: Creates tables, databases, indexes, etc.
ALTER: Modifies the structure of an existing object.
DROP: Deletes tables, databases, etc.
TRUNCATE: Removes all records from a table but retains the structure.
* Data Manipulation Language (DML):

Purpose: Handles the manipulation of data within tables.
Commands:
SELECT: Retrieves data from the database.
INSERT: Adds new records to a table.
UPDATE: Modifies existing records.
DELETE: Removes records from a table.
* Data Control Language (DCL):

Purpose: Manages permissions and access control.
Commands:
GRANT: Assigns privileges to users.
REVOKE: Removes privileges from users.

<h4> 4.What is the difference between a Primary Key and a Foreign Key? </h4>
Primary Key: Uniquely identifies each record in a table. It can't be NULL and must be unique.

Foreign Key: A field in one table that links to the Primary Key of another table, creating a relationship between them. It can be NULL or duplicate.

<h4> 5. What is an Entity-Relationship Diagram? </h4>
An Entity-Relationship (ER) Diagram is a visual representation of the entities (objects) in a database and their relationships. It helps in designing the structure of a database.


<h4> 6.What are the advantages of relational databases? </h4>
Data Integrity: Ensures accuracy and consistency with constraints like primary and foreign keys.
Flexibility: Allows easy data updates and retrieval with SQL.
Scalability: Can handle large amounts of data and transactions efficiently.
Security: Supports access control and user privileges.
Data Redundancy Reduction: Normalization minimizes duplicate data.
Ease of Use: Simple to query and manage with SQL.

<h4> 7. State four types of data type used to store data in tables? </h4>
INT: Used to store integer (whole number) values.
VARCHAR: Used to store variable-length strings (text).
DATE: Used to store date values (e.g., YYYY-MM-DD).
FLOAT: Used to store floating-point (decimal) numbers.

<h4> 8. What is the purpose of a database management system (DBMS)? </h4>
Store and manage data: Organizes data efficiently for easy access and retrieval.
Ensure data integrity and security: Enforces rules to maintain data accuracy and restrict unauthorized access.
Facilitate data manipulation: Allows users to insert, update, delete, and query data using SQL.
Enable concurrent access: Supports multiple users accessing and modifying data simultaneously without conflicts.
Backup and recovery: Provides mechanisms to protect data from loss and ensure recovery in case of failure.
