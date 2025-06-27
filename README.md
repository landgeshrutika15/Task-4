Task 4: Aggregate Functions and Grouping:

In this task, I learned how to analyze and summarize data in SQL using:

1. Aggregate Functions

Used SQL functions like:

SUM() – to calculate the total of a column (e.g., total salary)

AVG() – to find average values

COUNT() – to count rows or values

MAX() and MIN() – to find the highest and lowest values

2. GROUP BY Clause

I grouped rows based on a common column (e.g., department) to:

Summarize data per group

Apply aggregate functions for each group

Example:

SELECT department, AVG(salary)
FROM employee
GROUP BY department;

3. HAVING Clause

Using HAVING to filter grouped results based on aggregate values (unlike WHERE which filters individual rows).

Example:
HAVING AVG(salary) > 50000
