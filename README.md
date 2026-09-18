# World Cup Database

A PostgreSQL and Bash scripting project completed as part of the **freeCodeCamp Relational Database Certification**.

## Project Overview

This project involves creating a database of World Cup games using **PostgreSQL**.

The project uses a Bash script to enter information from World Cup games into the database and another Bash script to query the database for useful statistics. It focuses on creating tables, defining relationships, inserting data, writing SQL queries, and satisfying the required database constraints and tests.

## Technologies Used

- PostgreSQL
- SQL
- Bash
- Git
- GitHub

## Database Structure

The database contains information about World Cup teams and games.

The tables are related using PostgreSQL primary and foreign keys to represent the relationships between teams and their games.

## Data Included

The database contains World Cup game information, including:

- Teams
- Games
- Game rounds
- Game winners
- Game losers
- Goals scored by each team

The data is processed and inserted into the PostgreSQL database using the `insert_data.sh` Bash script.

## Project Requirements

The project was completed according to the freeCodeCamp requirements.

The project had to:

- Use PostgreSQL
- Create the required database tables
- Include primary keys
- Include foreign keys where required
- Insert the provided World Cup game data
- Create a Bash script to insert the game data
- Create a Bash script containing SQL queries
- Retrieve useful statistics from the database
- Pass all project tests
- Export the completed database as `worldcup.sql`
- Save the completed `insert_data.sh` file
- Save the completed `queries.sh` file

## Project Files

The main project files are:

```text
worldcup.sql
insert_data.sh
queries.sh
```
