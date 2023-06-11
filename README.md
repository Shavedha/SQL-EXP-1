# SQL - EXPERIMENT 1 - To fetch first name from the worker table using alias from the sample data using SQL query.
## AIM:
To fetch first name from the worker table using alias from the sample data using SQL query.

## ALGORITHM:
1. Create a table named "worker" with required columns.
2. Insert the sample data into the "worker" table.
3. Fetch the first names by executing the SQL query: "SELECT name AS FIRST_NAME FROM worker;".
4. Retrieve the result set containing the first names from the query execution.
5. Display or process the retrieved first names as needed.

## PROGRAM:
```
CREATE TABLE worker (
    id INT,
    name VARCHAR(50),
    age INT,
    salary DECIMAL(10, 2)
);
INSERT INTO worker (id, name, age, salary)
VALUES
    (1, 'John', 30, 5000.00),
    (2, 'Jane', 25, 4500.00),
    (3, 'Mike', 35, 6000.00),
    (4, 'Sarah', 28, 5500.00),
    (5, 'David', 32, 5200.00);
SELECT name AS FIRST_NAME
FROM worker;
```
## OUTPUT:
![image](https://github.com/Shavedha/SQL-EXP-1/assets/93427376/0c14e57a-f9eb-4ca7-b0f6-42d7e2ddf904)


## RESULT:
Thus, a sql query to fetch first name from worker table using alias from sample data is executed successfully.
