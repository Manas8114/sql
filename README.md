# sql

SQL practice repository — queries, schema designs, and database exercises for learning and reference.

## Contents

| File | Description |
|------|-------------|
| `*.sql` | SQL scripts: DDL (CREATE), DML (INSERT/UPDATE), DQL (SELECT/JOINs) |
| `schema/` | Database schema diagrams (ERD, normalization) |
| `exercises/` | Practice problems with solutions |
| `datasets/` | Sample data (CSV/SQL dump) for practice |

## Topics Covered

- **DDL**: CREATE TABLE, ALTER, DROP, constraints (PK, FK, UNIQUE, CHECK)
- **DML**: INSERT, UPDATE, DELETE, MERGE
- **DQL**: SELECT, WHERE, ORDER BY, GROUP BY, HAVING
- **Joins**: INNER, LEFT, RIGHT, FULL, CROSS, SELF
- **Subqueries**: Correlated, non-correlated, EXISTS, IN
- **Window Functions**: ROW_NUMBER, RANK, LAG/LEAD, aggregates
- **CTEs**: Recursive, multiple, materialized
- **Transactions**: BEGIN, COMMIT, ROLLBACK, isolation levels
- **Indexing**: B-tree, hash, partial, covering
- **Normalization**: 1NF–3NF, BCNF, denormalization tradeoffs

## Databases

- PostgreSQL (primary)
- MySQL / MariaDB (compatible)
- SQLite (for portable exercises)
- SQL Server (T-SQL notes where applicable)

## Run

```bash
# PostgreSQL
psql -d mydb -f schema.sql
psql -d mydb -f seed.sql
psql -d mydb -f queries.sql

# MySQL
mysql -u root -p mydb < schema.sql

# SQLite
sqlite3 practice.db < schema.sql
```

## Resources

- [PostgreSQL Docs](https://www.postgresql.org/docs/)
- [Use The Index, Luke](https://use-the-index-luke.com/)
- [SQLZoo](https://sqlzoo.net/)
- [LeetCode Database](https://leetcode.com/tag/database/)