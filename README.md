# DBMS Intro
A Database Management System (DBMS) is a type of software that allows users to define, create, and control data.

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/monehi-t/SQL_Notes/blob/main/database.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/monehi-t/SQL_Notes/blob/main/database.png">
  <img alt="Relationship between the user, DBMS, and the Database" src="https://github.com/monehi-t/SQL_Notes/blob/main/database.png">
</picture>


With databases you can:
  - Store, retrieve and update data;
  - Get metadata;
  - Access a database remotely;
  - Restrict access to data;
  - Make concurrent updates;
  - Recover to some point in time;
  - Check the rules for data consistency automatically.
_______________________________________________________________________________________________

# Relational Data Model
The Relational Data Model (RDM) is an abstract mathematical model on the basis of which modern databases are designed.

  - **Relation** = a two-dimensional table that represents some entity or relationship.
  - **Entity** = an abstraction of some object, for example, a student, a car, or a building.
  - **Relationship** = defines how entities are interconnected.
  - **Primary key(PK)** = a field that is used to uniquely identify each record in the table, guaranteeing that no two records in are identical.
  - **Referential integrity** = occurs when we have two connected relations.
  - **Foreign key(FK)** = an attribute of a relation that points to the primary key of another relation.



### Relationships
  * one-to-one relationship (1-1)
  * one-to-many relationship (1-M)
  * many-to-many (M-M) relationship
_______________________________________________________________________________________________

# SQL
SQL (Structured Query Language) is a domain-specific programming language designed to handle data in tables.
SQL is the standard data manipulation language used by data-driven companies around the world. 

### Basic SQL Data Types
- **INTEGER**: a numeric data type that represents some range of mathematical integers
- **VARCHAR**: a string of symbols of varying lengths not longer
- **BOOLEAN**: type represents boolean logic values: either TRUE or FALSE.
- **FLOAT**:  an approximate numeric data type used for floating-point numbers
- **DECIMAL(precision, scale)**: a numeric data type that represents integers with decimal point.
    - _Scale_: is the count of digits to the right of the decimal point.
    - _Precision_: is the total count of digits in the number
      <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/monehi-t/SQL_Notes/blob/main/DecimalDataType.png">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/monehi-t/SQL_Notes/blob/main/DecimalDataType.png">
    <img alt="Relationship between the user, DBMS, and the Database" src="https://github.com/monehi-t/SQL_Notes/blob/main/DecimalDataType.png">
    </picture>


## Arithmetic Expressions
The basic set of arithmetic operators supported in SQL is the following:
- _-_ unary minus that changes the sign of a value;
- _*_ multiplication;
- _/_ division;
- _%_ modulo that returns the remainder of integer division;
- _+_ addition;
- _-_ subtraction.

## Basic Create and Delete Statement
To create a database and table we use the following:
 * CREATE DATABASE _databaseName_;
 * CREATE TABLE _tableName_;

To delete a database and table we use the following:
 * DROP DATABASE _databaseName_;
 * DROP TABLE _tableName_;


