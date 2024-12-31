# Project 1 - SQL Queries for the `people` Table

This repository contains Project 1 for Databases. The project involves writing SQL queries to manipulate and retrieve data from a `people` table. Each task corresponds to a specific SQL operation, testing understanding of database CRUD operations.

## Project Structure

```plaintext
├── Databases_Project_1
│   ├── Project_1.ipynb
│   ├── Project_1.pdf
│   ├── book-DDL.sql
│   └── book-smallRelationsInsertFile.sql
└── projet1_settled.docx
```

## Table Schema

The `people` table is defined as follows:

```sql
CREATE TABLE people (
    id INTEGER PRIMARY KEY AUTO_INCREMENT UNIQUE NOT NULL,
    name TEXT NOT NULL,
    email TEXT,
    age INTEGER
);
```

Here are example records in the people table:

| id | name        | email                 | age |
|----|-------------|-----------------------|-----|
| 1  | Jay Summet  | summetj@fordham.edu   | 30  |
| 2  | Sally Smith | ssmith@fordham.edu    | 23  |

## Project Tasks

1. Insert a New Record
   - Add a new person to the table using your name and an email address of your choice. The id should be auto-generated, and the age field should not be specified.
2. Filter by Exact Age
   - Write a query to return only the name and email of records where the age is exactly 70.
3. Filter by Email Domain
   - Write a query to return only the name and email of records where the email address ends with gatech.edu.
4. Search for a Substring in Email
   - Return all columns of records where the email field contains "007" at any position.
5. Update a Specific Record
   - Update the email field of the record with the name "Jay Summet" to summetj (without any domain).
6. Delete Specific Records
   - Remove all records where the email field ends with nyu.edu.

## How to Use the File

1. Review the schema and tasks in `project1_settled.docx`.
2. Use a SQL console or database environment (as set up in `Assignment 1`) to execute the queries.
3. Verify that each query works as intended by observing the output.
