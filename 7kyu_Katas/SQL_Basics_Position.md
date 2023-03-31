# CodeWars Python Solutions

---

## SQL Basics - Position

You have access to a table of monsters as follows:

monsters schema

id
name
legs
arms
characteristics
In each row, the characteristic column has a single comma. Your job is to find it using position(). You must return a table with the format as follows:

output schema

id
name
comma
The comma column will contain the position of the comma within the characteristics string. Order the results by comma.

---

### Given Code


```sql
/*  SQL  */
```

---

### Solution


```sql
select id, name, position(',' in monsters.characteristics) as COMMA
from monsters
order by COMMA;
```

---


[See on CodeWars.com](https://www.codewars.com/kata/59401e0e54a655a298000040)
