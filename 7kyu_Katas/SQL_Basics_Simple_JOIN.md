# CodeWars SQL Solutions

---

## SQL Basics: Simple JOIN

For this challenge you need to create a simple SELECT statement that will return all columns from the products table, and join to the companies table so that you can return the company name.

products table schema
* id
* name
* isbn
* company_id
* price

companies table schema
* id
* name

You should return all product fields as well as the company name as "company_name".

NOTE: Your solution should use pure SQL. Ruby is used within the test cases to do the actual testing.

---

### Given Code


```sql
-- Create your SELECT statement here
```

---

### Solution


```sql
-- Create your SELECT statement here
select products.*, companies.name as company_name
from products
join companies on companies.id = products.company_id;
```

---


[See on CodeWars.com](https://www.codewars.com/kata/5802e32dd8c944e562000020)
