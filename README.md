# MySQL_Queries
```sql

-- The 'SELECT' statement is used to query the database and retrieve data from one or more tables
SELECT column1, column2, ...
FROM table_name;

-- The 'WHERE' clause is used to filter records based on specific conditions
SELECT column1, column2, ...
FROM table_name
WHERE condition;

-- The 'ORDER BY' clause is used to sort the result set in either ascending or descending order
SELECT column1, column2, ...
FROM table_name
ORDER BY column1 ASC|DESC, column2 ASC|DESC, ...;

-- The 'LIMIT' clause is used to specify the number of records to return
SELECT column1, column2, ...
FROM table_name
LIMIT number;

-- You can combine these clauses to create more complex queries
SELECT first_name, last_name, email
FROM customers
WHERE country = 'USA'
ORDER BY last_name ASC
LIMIT 10;


-- Select a String Value
SELECT 'MyFirstValue';

-- Select a String Value with Alias
SELECT 'MyFirstValue' AS SomeValue;

-- Select an Arithmetic Operation Result
SELECT 1 + 1;

-- Select an Arithmetic Operation Result with Alias
SELECT 1 + 1 AS TWO;

-- Get Current DateTime
SELECT NOW();

-- Get Current Date
SELECT CURDATE();

-- Get Current Time
SELECT CURTIME();

--Display the Value of Pi
SELECT PI();

-- Find Remainder of a Division
SELECT 45 % 7 AS Remainder;

-- Find Square Root of a Value
SELECT SQRT(25) AS SquareRoot;
