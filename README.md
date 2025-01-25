University Library Management System Database
This project is a university library management system database designed and implemented as part of an academic project. The system models and manages library operations using a structured database approach, ensuring efficiency, accuracy, and performance optimization.

Key Highlights
Database Design

Created an Entity-Relationship Diagram (ERD) to model the library scenario.
Developed a logical model and normalized the database to 3rd Normal Form (3NF) for data integrity.
Implemented the logical model in MS SQL Server with sample data.
Constraints and Rules

Defined and enforced primary keys, foreign keys, unique constraints, check constraints, and default values for data consistency.
Database Features

Triggers:
Trigger 1: Prevent the deletion of a book if it is currently borrowed.
Trigger 2: Automatically calculate and update fines for overdue books.
Views:
View 1: A summary view for library staff showing borrowed books and their due dates.
View 2: A member-specific view displaying their borrowed books and outstanding fines.
Indexes:
Index 1: Optimized for querying borrowed items by member ID and borrowing period.
Index 2: Optimized for retrieving outstanding fines for a member.
Stored Procedures:
Procedure 1: Retrieve all items borrowed by a member within a specified period.
Procedure 2: Retrieve the outstanding fines for a given member.
Project Deliverables
ERD: Visual representation of the database structure.
SQL Scripts: Includes scripts for creating tables, inserting sample data, defining constraints, and implementing triggers, views, stored procedures, and indexes.
Documentation: Explains the design decisions, use cases, and implementation details.

Installation and Usage

Clone the repository
Import the SQL scripts into MS SQL Server.
Execute the scripts in the following order:
Schema creation and data insertion scripts.
Triggers, views, procedures, and indexes.
Test the database using the provided sample queries and stored procedures.
Technologies Used
Database Management System: Microsoft SQL Server
Design Tools: ERD and logical model diagrams (created using  Draw.io, SQL Server Management Studio])


Database Vulnerabilities and Mitigation Techniques
Objective
This project focuses on analyzing two critical database vulnerabilities, their techniques of exploitation, their impact, and countermeasures to mitigate these vulnerabilities. It includes detailed research, practical examples, and mitigation strategies.
