# MySQL Scripts for Database Management

This repository contains a series of SQL scripts designed to manage and manipulate databases and tables in MySQL. Below is a concise description of each script and its corresponding task.

---

### `0-list_databases.sql`
**Task**: List all databases in your MySQL server.
- **Description**: This script will retrieve and display the names of all databases available in your MySQL server.

---

### `1-create_database_if_missing.sql`
**Task**: Create the database `hbtn_0c_0` if it does not already exist.
- **Description**: This script checks whether the database `hbtn_0c_0` exists and creates it if it is missing.

---

### `2-remove_database.sql`
**Task**: Delete the database `hbtn_0c_0`.
- **Description**: This script deletes the database `hbtn_0c_0` from the MySQL server.

---

### `3-list_tables.sql`
**Task**: List all tables in a given database.
- **Description**: This script lists all tables within the currently selected database in your MySQL server.

---

### `4-first_table.sql`
**Task**: Create a table `first_table` in the current database.
- **Description**: This script creates a table called `first_table` in the selected database with the necessary structure.

---

### `5-full_table.sql`
**Task**: Describe the structure of the `first_table`.
- **Description**: This script prints the detailed description (schema) of the `first_table` from the `hbtn_0c_0` database.

---

### `6-list_values.sql`
**Task**: List all rows in the `first_table` of `hbtn_0c_0` database.
- **Description**: This script retrieves and lists all records (rows) from the table `first_table` in the `hbtn_0c_0` database.

---

### `7-insert_value.sql`
**Task**: Insert a new row into `first_table`.
- **Description**: This script inserts a new record into the `first_table` in the `hbtn_0c_0` database.

---

### `8-count_89.sql`
**Task**: Count the number of records with `id = 89` in `first_table`.
- **Description**: This script counts the number of rows where the `id` equals `89` in the `first_table` of the `hbtn_0c_0` database.

---

### `9-full_creation.sql`
**Task**: Create the `second_table` and insert multiple rows into it.
- **Description**: This script creates the table `second_table` in the `hbtn_0c_0` database and inserts several records into it.

---

### `10-top_score.sql`
**Task**: List all records from the `second_table`.
- **Description**: This script lists all records from the `second_table` in the `hbtn_0c_0` database.

---

### `11-best_score.sql`
**Task**: List all records with a score greater than or equal to `10` from `second_table`.
- **Description**: This script retrieves and displays all records from the `second_table` where the `score` is greater than or equal to `10`.

---

### `12-no_cheating.sql`
**Task**: Update the score of "Bob" to `10` in `second_table`.
- **Description**: This script updates the `score` field for the record where the name is "Bob" to `10` in the `second_table` of the `hbtn_0c_0` database.

---

### `13-change_class.sql`
**Task**: Remove all records with a score of `5` or less from `second_table`.
- **Description**: This script deletes all records from the `second_table` where the `score` is less than or equal to `5`.

---

### `14-average.sql`
**Task**: Compute the average score of all records in `second_table`.
- **Description**: This script calculates the average of the `score` column for all records in the `second_table`.

---

### `15-groups.sql`
**Task**: List the number of records for each distinct score in `second_table`.
- **Description**: This script counts the number of occurrences of each distinct `score` in the `second_table` and groups them accordingly.

---

### `16-no_link.sql`
**Task**: List all records in the `second_table` from `hbtn_0c_0`.
- **Description**: This script retrieves and lists all records from the `second_table` of the `hbtn_0c_0` database.

---

Each script focuses on a specific database operation, from listing databases and tables to manipulating data within them.
