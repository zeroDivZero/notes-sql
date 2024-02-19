# GETTING STARTED

Basic syntax (components) of every SQL query:

* `SELECT` to choose columns to retrieve data.
* `FROM` to choose tables where columns are located.
* `WHERE` to filter data.

Example:

```sql
SELECT
  customer_id,
  first_name,
  last_name
FROM
  customer_data.customer_name
WHERE
  first_name = 'Tony'
  AND age >= 65
```

Other logical operators for `WHERE` clause include `OR` and `NOT`.
