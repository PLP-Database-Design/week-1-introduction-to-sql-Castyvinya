#State and Explain the components of a DBMS(Database Management System)

They include the following;
Database: Stores the data in an organized way for efficient access and management.
DBMS Software: Manages the database and provides an interface for users to interact with the data.
Query Processor: Processes user queries (e.g., SQL commands) and converts them into operations on the database.
Database Engine: Handles data storage, retrieval, and updating.
Metadata: Data about the database structure (e.g., table schemas and relationships).



#What is a relational database? Give 4 examples.

Refers to type of database that stores data in tables with rows and columns.Relationships between data are established using keys.Examples include the following;MySQL
                                    PostgreSQL
                                    SQLite
                                    Microsoft SQL Server


#State and Explain three classifications of SQL?

DDL (Data Definition Language): defines and modifies database structures using the following commands;
     CREATE- creates a new table
     ALTER- modifies an existing database.
     DROP -deletes an entire table.

DML (Data Manipulation Language):manages data within tables using the following commands;
     SELECT- retrieves certain records from one or more tables.
     INSERT- creates a record.
     UPDATE- modifies records.
     DELETE- deletes records.

DCL (Data Control Language): controlls access to the database using the following commands;
    GRANT- gives a previlege to the user.
    REVOKE- takes back previleges granted by the user.




#What is the difference between a Primary Key and a Foreign Key?

A Primary Key is unique identifier for each record in a table which ensures no duplicate values,while a Foreign Key is a field in one table that links to the primary key in another table. Establishes relationships between tables.


#What is an Entity-Relationship Diagram?

An Entity-Relationship Diagram (ERD) is a visual representation of entities (tables), their attributes (columns), and relationships (connections between tables) in a database.


#What are the advantages of relational databases?

Data Integrity: Maintains accuracy and consistency of data.
Scalability: Handles large amounts of data efficiently.
Flexibility: Allows complex queries and relationships.
Security: Provides user-based access controls


#State four types of data type used to store data in tables?

INTEGER: For whole numbers.
VARCHAR: For variable-length text.
DATE: For dates.
BOOLEAN: For true/false values.


#What is the purpose of a database management system (DBMS)?

A DBMS provides tools to:
Store, retrieve, and manipulate data.
Ensure data integrity and security.
Manage concurrent data access by multiple users.