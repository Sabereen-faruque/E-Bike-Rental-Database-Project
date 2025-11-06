# E-Bike Rental Database Project

**Course:** Data Management & Business Process Modeling (MSc)  
**Stack:** SQL (MariaDB), ERD (Lucidchart/draw.io), DBeaver

## What this repo contains
- **ERD_Models/** – Conceptual, Logical, and Physical ER diagrams (PDFs)
- **DDL_Scripts/** – Table creation scripts (PK/FK, CHECK, UNIQUE)
- **Data_Population/** – Sample data + count report SQL
- **SQL_Reports/** – 5 reports (joins, subqueries, CASE, views, aggregates)

## Highlights
- 3NF schema with full referential integrity and resolved M:N relationships  
- Supertype–Subtype modeling for Bikes (E-Bike, Classic Bike)  
- Reports on bike utilization, rider activity, and revenue trends

## How to run
1. Create a MariaDB schema.
2. Run `DDL_Scripts/*.sql` to create tables and constraints.
3. Load data from `Data_Population/`.
4. Execute queries from `SQL_Reports/`.

## License
Personal academic project — view only.
