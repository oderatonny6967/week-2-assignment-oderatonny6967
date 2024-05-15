# Week 2: Essential Data Retrieval & Filtering (Focus on Expense Tracker Data)

This week, we'll dive deeper into your Expense Tracker project by mastering essential techniques for retrieving and manipulating your financial data! We'll explore the SELECT statement to extract specific information and leverage the power of filtering with the WHERE clause. Finally, we'll learn to organize our results using ORDER BY.

## Learning Objectives:

* Utilize the SELECT statement to retrieve data from the Expense Tracker database.
* Apply wildcards (%) and comparison operators for targeted data retrieval.
* Employ the WHERE clause with logical operators (AND, OR, NOT) to filter data effectively.
* Organize retrieved data using the ORDER BY clause.
  
## Instructions
This assignment is designed to be completed in approximately 2 hours.

What you'll need:

Access to a computer with internet access
A text editor (e.g. Microsoft Word Docs)
Access to a sample Expense Tracker database (or instructor-provided data) that includes the table you designed in Week 1 (likely named "Expenses"). See the database script in this repo titled "Week2.txt"
Scenario: Imagine you've been diligently tracking your expenses using the Expense Tracker database you designed last week. Now, it's time to analyze your spending habits!

## Submission:

Save your completed assignment as a document (e.g., .docx, .txt)
Submit your document by uploading or pushing your document through on to this repo


## Part 1: Retrieving Data with SELECT (30 minutes)

Based on the Expense Tracker table you designed in Week 1, which likely includes columns like "expense_id," "amount," "date," and "category," complete the following tasks:

**1.1 Retrieving All Expenses:**

Write a SQL query to retrieve all data points (columns) from the "Expenses" table.

**1.2 Specific Columns:** 

Modify your query to select only specific columns relevant to your analysis.For example, you might choose "date," "category," and "amount" to analyze spending patterns by category and date.

**1.3 Filtering by Date Range:** 
Write a query to retrieve expenses charged between a specific date range (e.g., January 1, 2024, to February 15, 2024).
Remember to use the appropriate data type for the "date" column when specifying the date range in your query.

## Part 2: Filtering with WHERE Clause (45 minutes)

**2.1 Filtering by Category:** 
Write a query to find all expenses belonging to a specific category (e.g., "Entertainment").

**2.2 Filtering with Comparison Operators:** 
Find expenses with an amount greater than a certain value (e.g., $50).

**2.3 Combining Filters (AND):**  
Refine your query to find expenses that meet multiple criteria. For example, you might search for expenses greater than $75 AND belonging to the "Food" category.

**2.4 Combining Filters (OR):** 
Modify your query to find expenses belonging to one category or another (e.g., "Transportation" OR "Groceries").

**2.5 Filtering with NOT:** 
Write a query to display expenses that are NOT related to a specific category (e.g., "Rent").

## Part 3: Sorting Retrieved Data (45 minutes)

**3.1 Sorting by Amount:** 
Write a query to display all expenses sorted by amount in a specific order (e.g., descending order for highest to lowest spending).

**3.2 Sorting by Date and Category:**  
Modify your query to sort expenses based on multiple columns. For example, you might sort first by date (descending order) and then by category (ascending order) to see recent spending trends by category.
