# Relational Database Design: University Bookstore

### Project Introduction
* Designing a relational database for a college bookstore such as University of Washington Seattle bookstore  
* Creating the Entity Relationship Diagram for the bookstore, whose business is to sell books and merchandise in the state
* Creating SQL schema that stores information about daily transactions of the bookstore at various store locations


### Entity-Relationship Diagram
![ERD](https://github.com/amruta-11/university-bookstore-design/blob/main/FinalERD.png)


### SQL code:
[This file](https://github.com/amruta-11/university-bookstore-design/blob/main/sql-code.txt) includes code for:
- Creating Customer, Store, State and Order table
- Code to insert 5 records into each of these coloumns
- Stored Procedure:
    - Inserting data into Orders Table
    - Creating stored procedure to insert data into 'Pen' Table
- Business Rule: The age of the customer that orders from the book store should be greater than or equal to 8
- Computed column: Find total amount spend by each customer
