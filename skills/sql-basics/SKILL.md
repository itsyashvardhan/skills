---
name: sql-basics
description: Write, explain, debug, and optimize basic SQL queries. Use for SELECT queries, joins, filters, grouping, aggregations, CTEs, window functions, schema inspection, data validation, and beginner-friendly SQL explanations.
---

# SQL Basics

Write SQL that is correct, readable, and easy to verify.

## Workflow

1. Inspect table names, columns, keys, grain, and date fields before querying.
2. Start with a small row sample or count query when exploring data.
3. Make joins explicit and check cardinality.
4. Validate aggregations with row counts and totals.
5. Use CTEs to make multi-step logic readable.
6. Avoid destructive statements unless explicitly requested and backed up.

## Style

Prefer clear aliases, named CTEs, and comments only for non-obvious business logic.
