# WILDCARD

In `SELECT` and `WHERE` clauses, can use wildcard `%` (some systems use `*`) to match one or more characters.

E.g.:

```sql
WHERE field1 LIKE 'Ch%'
```

matches *Chavez* and *Chen*.

## Select All

`SELECT *` selects all columns. Be sure that's intended, since it may return huge amount of data and impacts performance.
