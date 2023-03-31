# CodeWars SQL Solutions

---

## Adults only (SQL for Beginners #1)


In your application, there is a section for adults only. You need to get a list of names and ages of users from the users table, who are 18 years old or older.

users table schema

* name
* age

NOTE: Your solution should use pure SQL. Ruby is used within the test cases just to validate your answer.

---

### Given Code


```sql
--Your code here
```

---

### Solution


```sql
SELECT *
FROM users
WHERE age >= 18;
```

---


[See on CodeWars.com](https://www.codewars.com/kata/590a95eede09f87472000213)
