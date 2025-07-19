Family & Employment Database (SQL Project)

This project presents a relational database in **Microsoft SQL Server** that models:

- People and their family relationships (parents, spouse)
- Companies and employment contracts
- Salary analysis and query logic

Tables

- `Osoba` – people with family links
- `Firma` – companies with a CEO (one per company)
- `Zatrudnienie` – employment relation (one person can work in many firms)

Example queries

- A. Find a person with the most granddaughters
- B. Count employees and average salary per contract type
- C. Show the 2-generation family of the lowest-earning person

Files

- `schema.sql` – database schema and sample data
- `queries.sql` – business logic (A, B, C)
- `diagram.png` – ERD schema
- `README.md` – this file

Tools

- SQL Server 2019 / SSMS
- ERD created with dbdiagram.io
