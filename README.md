# sql

SQL practice repository — queries, schema designs, and database exercises for learning and reference.

## Contents

| File | Description |
|------|-------------|
| `schema/` | DDL scripts (CREATE TABLE, indexes, constraints) |
| `queries/` | DML/DQL exercises (SELECT, JOIN, subqueries, window functions) |
| `procedures/` | Stored procedures, functions, triggers |
| `datasets/` | Sample data (CSV/SQL inserts) for practice |
| `normalization/` | 1NF→3NF/BCNF exercises with solutions |

## Topics Covered

| Category | Examples |
|----------|----------|
| **DDL** | CREATE, ALTER, DROP, constraints (PK, FK, UNIQUE, CHECK) |
| **DML** | INSERT, UPDATE, DELETE, MERGE |
| **DQL** | SELECT, WHERE, ORDER BY, GROUP BY, HAVING |
| **Joins** | INNER, LEFT, RIGHT, FULL, CROSS, SELF |
| **Subqueries** | Correlated, non-correlated, EXISTS, IN, ANY/ALL |
| **Window Functions** | ROW_NUMBER, RANK, LAG/LEAD, NTILE, aggregates |
| **CTEs** | Recursive, multiple, materialized |
| **Transactions** | BEGIN, COMMIT, ROLLBACK, isolation levels |
| **Indexing** | B-tree, hash, partial, covering, statistics |
| **Performance** | EXPLAIN ANALYZE, query tuning |

## Databases

- PostgreSQL (primary)
- MySQL / MariaDB (compatible)
- SQLite (for portable exercises)
- SQL Server (T-SQL notes where applicable)

## Run

```bash
# PostgreSQL
psql -d practice_db -f schema/create_tables.sql
psql -d practice_db -f datasets/seed.sql

# MySQL
mysql -u root -p practice_db < schema/create_tables.sql

# SQLite
sqlite3 practice.db < schema/create_tables.sql
```

## Resources

- [PostgreSQL Docs](https://www.postgresql.org/docs/)
- [Use The Index, Luke](https://use-the-index-luke.com/)
- [SQLZoo](https://sqlzoo.net/)
- [LeetCode Database](https://leetcode.com/tag/database/)