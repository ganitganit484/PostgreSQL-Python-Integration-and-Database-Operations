# PostgreSQL & Python Database Operations (`psycopg3`)
**View Interactive Report:** [Live HTML Report](https://ganitganit484.github.io/PostgreSQL-Python-Integration-and-Database-Operations/)
This repository demonstrates relational database management, schema operations, and SQL querying via **Python** using the `psycopg3` library. 

The project focuses on safe database interactions, handling edge cases, dynamic schema manipulation, and executing atomic SQL operations.

## Key Implementation Highlights

* **Safe Connection & Parameterized Queries:** Implemented dynamic database querying using parameterized SQL statements (`%s`) to prevent SQL injection vulnerabilities.
* **Relational Schema & Constraints:** Designed and interacted with linked tables (`students`, `enrollments`, `courses`) utilizing foreign keys, `UNIQUE` constraints, and primary keys.
* **Atomic Transactions & Error Handling:** Built robust operations (e.g., student enrollment) wrapped in explicit `commit()` and `rollback()` blocks to ensure data integrity during database errors.
* **Complex Relational Queries:** Wrote optimized SQL queries using `LEFT JOIN`, `GROUP BY`, `HAVING`, and `ON CONFLICT DO NOTHING` logic to handle duplicate inserts and analyze student enrollment patterns[cite: 4].
* **Database Metadata Inspection:** Developed utility functions to query PostgreSQL's `information_schema` to dynamically read table columns and structure[cite: 4].

## Tech Stack
* **Database:** PostgreSQL[cite: 4]
* **Language:** Python 3[cite: 4]
* **Database Adapter:** `psycopg` (v3)[cite: 4]

## Repository Files
* `PostgreSQL_Python_Database_Operations.ipynb` - Jupyter Notebook containing complete database wrapper functions, schema setups, and execution examples[cite: 4].
