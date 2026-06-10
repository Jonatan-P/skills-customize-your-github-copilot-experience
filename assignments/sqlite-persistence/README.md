# 📘 Assignment: Python Persistence with SQLite

## 🎯 Objective

Learn how to store, retrieve, and manage data using SQLite in Python so your program can preserve information between runs.

## 📝 Tasks

### 🛠️ Create a SQLite database and schema

#### Description
Set up a local SQLite database and define a table structure for storing records.

#### Requirements
Completed program should:

- Use Python's built-in `sqlite3` module
- Create or open a local SQLite database file
- Define a table with columns for `id`, `title`, `content`, and `created_at`
- Use `CREATE TABLE IF NOT EXISTS` to ensure the table is created safely


### 🛠️ Implement CRUD operations

#### Description
Build Python functions to create, read, update, and delete records in the SQLite database.

#### Requirements
Completed program should:

- Add new records using parameterized SQL statements
- List all records from the database
- Update a record by `id`
- Delete a record by `id`
- Handle missing records gracefully with clear messages


### 🛠️ Build a command-line interface

#### Description
Create a simple CLI menu so users can interact with the SQLite database from the terminal.

#### Requirements
Completed program should:

- Show menu options for add, list, update, delete, and exit
- Request input for record fields and record IDs
- Refresh the displayed data after each operation
- Exit cleanly when the user chooses to quit
