# [CONTINUE](https://learning.oreilly.com/library/view/practical-sql-2nd/9781098129866/c14.xhtml#h2-501065c14-0008)
## Date
9/19/2023

## Notes:

To make a case sensitive match use:
`WHERE ~`
To make a case insensitive match use:
`WHERE ~*`

---

The inner join will show results from both tables where the rows match whereas an intersection will only show the matching tables and present them in a column that matches the first table.

---

Order by the selected column (e.g. 1 is last_name here)
```
SELECT last_name, first_name, salary FROM teachers ORDER BY 1 DESC;
``` 