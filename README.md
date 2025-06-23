# SQL-Developer-Intership-Task1-
Library Operations Database:
A relational database schema designed for managing core operations in a Library Management System, including books, members, staff, reservations, loans, and fines.

Project Structure
SQL Script for Schema.sql – SQL script to create all tables with relationships
sample_data.sql – Insert statements with realistic sample data
ER Diagram.png – ER diagram showing entity relationships
README.md – Project summary and documentation
output.png-The output for sample_data
entities and relationships- description of entities and relationship between them 

Features
Tracks library members and staff
Handles book loans, reservations, and fine management
Includes proper use of primary keys, foreign keys, and constraints
Designed with normalization and scalability in mind
In this project, we explored the design and implementation of a relational database system for a Library Operations Management System. The goal was to understand how to model real-world scenarios using structured data, define relationships between entities, and implement them using SQL.

Brief review:

1.Domain Selection
Selected the Library domain, focusing specifically on operations like:
i.Managing books
ii.Tracking members and staff
iii.Handling reservations and loans
iv.Managing fines for late returns

2.Entity and Relationship Design
Identified core entities:Books, Members, Staff, Reservations, Loans, and Fines and relationships such as: 
i.A member can borrow/reserve multiple books
ii.Loans are managed by staff and can generate fines
iii.Schema Design and Normalization

3.Created a normalized database schema using:
i.Primary keys for unique identification
ii.Foreign keys for relational integrity
iii.Appropriate data types and constraints

4.SQL Script Creation
Wrote SQL CREATE TABLE statements to define the full schema, covering:
i.Entity structures
ii.Data relationships
iii.Key constraints

5.Data Insertion:
Added sample data using INSERT INTO statements to simulate realistic records (books, members, staff, loans, etc.), making the schema testable.

6.ER Diagram Generation
Created an Entity-Relationship diagram to visually represent how entities interact showing Operational workflows


License:
This project is an open-source. No license specified.

