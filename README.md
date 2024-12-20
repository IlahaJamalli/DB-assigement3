# DB-assigement3

## Description
This project demonstrates the normalization process for a sample database. The data starts in an unnormalized form and is progressively normalized through First Normal Form (1NF), Second Normal Form (2NF), and Third Normal Form (3NF). The database manages information about courses, books, authors, and publishers, ensuring data consistency, minimizing redundancy, and improving query efficiency.


1. First Normal Form (1NF):
   - Break multi-valued fields (e.g., authors) into separate rows.
   - Create the FirstNf_Table table.

2. Second Normal Form (2NF):
   - Remove partial dependencies by splitting data into separate tables:
     - SecondNf_Courses
     - SecondNf_Books
     - SecondNf_Authors
     - SecondNf_Book_Authors
     - SecondNf_Course_Books

3. Third Normal Form (3NF):
   - Remove transitive dependencies:
     - ThirdNf_Publisher
     - ThirdNf_Books
     - ThirdNf_Books_Publisher

- Creating Join Tables-
  Show relationship between tables
   
## Output
The project results in a normalized database with the following:
1. Well-structured tables designed according to database normalization principles.
2. Minimal redundancy and improved data integrity.
3. Join tables to handle many-to-many relationships effectively.
