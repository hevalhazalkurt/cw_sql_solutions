# CodeWars SQL Solutions

---

## Easy SQL - Ordering


Your task is to sort the information in the provided table 'companies' by number of employees (high to low). Returned table should be in the same format as provided:

companies table schema

* id
* ceo
* motto
* employees
* Solution should use pure SQL. Ruby is only used in test cases.

---

### Given Code


```sql
/*  SQL  */
```

---

### Solution


```sql
SELECT *
FROM companies
ORDER BY employees DESC;
```

---


[See on CodeWars.com](https://www.codewars.com/kata/593ed37c93350098d600001d)
