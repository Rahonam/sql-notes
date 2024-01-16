# SQL Query Compilation

This repository serves as a comprehensive compilation of SQL queries along with detailed explanations. The queries are organized into folders based on their types, covering Data Definition Language (DDL), Data Query Language (DQL), Data Manipulation Language (DML), Data Control Language (DCL), and Transaction Control Language (TCL).

## Table of Contents

- [DDL (Data Definition Language)](./ddl)
  - [Tables](./ddl/tables)
  - [Indexes](./ddl/indexes)
  - [Views](./ddl/views)
  - [Constraints](./ddl/constraints)

- [DML (Data Manipulation Language)](./dml)
  - [Select](./dml/select)
  - [Insert](./dml/insert)
  - [Update](./dml/update)
  - [Delete](./dml/delete)

- [DQL (Data Query Language)](./dql)
  - [Basic Queries](./dql/basic_queries)
  - [Aggregation](./dql/aggregation)
  - [Joins](./dql/joins)

- [DCL (Data Control Language)](./dcl)
  - [Grant](./dcl/grant)
  - [Revoke](./dcl/revoke)

- [TCL (Transaction Control Language)](./tcl)
  - [Transactions](./tcl/transactions)
  - [Commit and Rollback](./tcl/commit_rollback)
  

## Categories

### DDL (Data Definition Language)

#### Tables

- [Create Table](./ddl/tables/create_table.sql): SQL script to create a new table.
- [Alter Table](./ddl/tables/alter_table.sql): SQL script for modifying an existing table structure.
- [Drop Table](./ddl/tables/drop_table.sql): SQL script to remove a table from the database.

#### Indexes

- [Create Index](./ddl/indexes/create_index.sql): SQL script to create an index on a table.
- [Drop Index](./ddl/indexes/drop_index.sql): SQL script to remove an index from a table.

#### Views

- [Create View](./ddl/views/create_view.sql): SQL script to create a view.
- [Alter View](./ddl/views/alter_view.sql): SQL script for modifying an existing view.
- [Drop View](./ddl/views/drop_view.sql): SQL script to remove a view.

#### Constraints

- [Primary Key](./ddl/constraints/primary_key.sql): SQL script to add a primary key constraint.
- [Foreign Key](./ddl/constraints/foreign_key.sql): SQL script to add a foreign key constraint.
- [Check Constraint](./ddl/constraints/check_constraint.sql): SQL script to add a check constraint.

### DML (Data Manipulation Language)

#### Select

- [Basic Select](./dml/select/basic_select.sql): Basic SQL query to retrieve data from a table.
- [Select with Conditions](./dml/select/select_with_conditions.sql): SQL query with conditions to filter data.
- [Join Tables](./dml/select/join_tables.sql): SQL query demonstrating table joins.

#### Insert

- [Insert Values](./dml/insert/insert_values.sql): SQL script for adding new records to a table.
- [Insert with Subquery](./dml/insert/insert_with_subquery.sql): SQL script to insert data using a subquery.

#### Update

- [Update Records](./dml/update/update_records.sql): SQL script to modify existing records in a table.
- [Update with Join](./dml/update/update_with_join.sql): SQL script for updating records using a join.

#### Delete

- [Delete Records](./dml/delete/delete_records.sql): SQL script to remove records from a table.
- [Delete with Join](./dml/delete/delete_with_join.sql): SQL script for deleting records using a join.

### DQL (Data Query Language)

#### Basic Queries

- [Basic Select](./dql/basic_queries/basic_select.sql): Basic SQL queries for data retrieval.
- [Filtering and Sorting](./dql/basic_queries/filtering_sorting.sql): SQL queries with filtering and sorting.

#### Aggregation

- [Group By](./dql/aggregation/group_by.sql): SQL script to group data using the GROUP BY clause.
- [Aggregate Functions](./dql/aggregation/aggregate_functions.sql): SQL queries using aggregate functions (COUNT, SUM, AVG).

#### Joins

- [Inner Join](./dql/joins/inner_join.sql): SQL script for performing inner joins.
- [Left Join](./dql/joins/left_join.sql): SQL script for performing left joins.
- [Subqueries](./dql/joins/subqueries.sql): SQL script for using subqueries in joins.

### DCL (Data Control Language)

#### Grant

- [Grant Permissions](./dcl/grant/grant_permissions.sql): SQL script to grant permissions to a user.

#### Revoke

- [Revoke Permissions](./dcl/revoke/revoke_permissions.sql): SQL script to revoke permissions from a user.

### TCL (Transaction Control Language)

#### Transactions

- [Begin Transaction](./tcl/transactions/begin_transaction.sql): SQL script to begin a transaction.
- [Savepoint](./tcl/transactions/savepoint.sql): SQL script to create a savepoint within a transaction.

#### Commit and Rollback

- [Commit](./tcl/commit_rollback/commit.sql): SQL script to commit a transaction.
- [Rollback](./tcl/commit_rollback/rollback.sql): SQL script to rollback a transaction.

## Contributing

Feel free to contribute by adding new queries or improving existing ones. Follow these steps:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-query`.
3. Commit your changes: `git commit -m 'Add a new query'`.
4. Push to the branch: `git push origin feature/new-query`.
5. Submit a pull request.

