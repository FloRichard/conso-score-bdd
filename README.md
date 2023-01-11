# conso-score-bdd

This repository contains the SQL scripts used to create the conso-score database.

## File structure

- `/database` contains the sql and bash scripts to create the database
- `/doc` contains documentation

At the root of this project, you can find a docker-compose.

## Deploy the database

Go to the root of the project, and input `docker-compose up` in a terminal.

Docker must be installed.

## Database scheme

![Database scheme](./doc/projet-intensif-bdd.png)

Legend:

- A box is a table
- Fields are represented as follow: `<field name> <type>`
- Underscored field are primary keys
- Blue colored field are foreign keys
