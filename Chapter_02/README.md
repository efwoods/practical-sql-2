# Practical SQL, 2nd Edition
### A Beginner's Guide to Storytelling with Data

[PracticalSQL, 2nd Edition](https://nostarch.com/practical-sql-2nd-edition/) by Anthony DeBarros is [available from No Starch Press](https://nostarch.com/practical-sql-2nd-edition/).

### Chapter 2: Creating Your First Database and Table

Introduces PostgreSQL, the pgAdmin user interface, and the code for loading a simple data set about teachers into a new database.

### New Techniques
#### Order by the selected column (e.g. 1 is last_name here)
```
SELECT last_name, first_name, salary FROM teachers ORDER BY 1 DESC;
``` 