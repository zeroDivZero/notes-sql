# ALIAS

Can assign new name to column or table name to make it easier to work with (avoids comments).

```sql
field1 AS last_name
table AS customers

SELECT
  last_name
FROM
  customers
WHERE
  last_name LIKE 'Ch%';
```

Good for duration of query. Doesn't change actual name in database.
