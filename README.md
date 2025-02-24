# Introduction to SQL
## SELECT
SELECT * FROM Customers;
## SELECT
SELECT CustomerName,City FROM Customers;
## SELECT * FROM Customers
WHERE Country='Mexico';
## SELECT * FROM Products
ORDER BY Price;
## SELECT * FROM Customers
WHERE Country = 'Spain' AND CustomerName LIKE 'G%';
## SELECT * FROM Customers
WHERE Country = 'Germany' OR Country = 'Spain';
## SELECT * FROM Customers
WHERE NOT Country = 'Spain';
## INSERT INTO table_name (column1, column2, column3, ...)
VALUES (value1, value2, value3, ...);
## SELECT column_names
FROM table_name
WHERE column_name IS NULL;
## UPDATE table_name
SET column1 = value1, column2 = value2, ...
WHERE condition;
## DELETE FROM table_name WHERE condition;
