#  Task 3: SQL for Data Analysis – Data Analyst Internship

This project demonstrates my ability to manipulate and analyze structured data using SQL. I used a real-world e-commerce dataset and wrote various queries to extract meaningful insights.

---

##  Files Included

- `E-commerce Dataset.csv` – The original dataset.
- `orders.csv` – Split datasets to demonstrate JOIN operations.
  
##  Tools Used

- SQL (MySQL Workbench)
- word (for editing)
- GitHub (vers
  
# Interview Questions
### 1. What is the difference between WHERE and HAVING?
WHERE filters rows before aggregation.
HAVING filters groups after aggregation with GROUP BY.

### 2. What are the different types of joins?
INNER JOIN, LEFT JOIN, RIGHT JOIN, and FULL JOIN.
They combine rows from two or more tables based on a related column.

### 3. How do you calculate average revenue per user in SQL?
SELECT AVG(Total_Sales) FROM (
  SELECT Customer_Id, SUM(Sales) AS Total_Sales FROM ecommerce GROUP BY Customer_Id
) AS UserRevenue;

### 4. What are subqueries?
A subquery is a query nested inside another query.
It can be used in SELECT, FROM, or WHERE clauses to filter or compute values.

### 5. How do you optimize a SQL query?
Use indexes on frequently filtered or joined columns.
Avoid SELECT *, use EXPLAIN, and write efficient subqueries or views.

### 6. What is a view in SQL?
A view is a virtual table created from a SQL query.
It simplifies complex queries and improves readability.

### 7. How would you handle NULL values in SQL?
Use IS NULL or IS NOT NULL to filter.
Replace them with default values using COALESCE() or IFNULL().

