# Task 22: SQL Filtering Practice

## 1. Project Overview
This project focuses on practising SQL filtering techniques using sample customer and product data in Google Colab. It demonstrates how to filter records based on specific conditions, match text patterns, select values within ranges, and combine multiple conditions.

## 2. Objective
- Practise SQL filtering using `WHERE`.
- Select multiple values using `IN` and `NOT IN`.
- Filter numeric values using comparison operators.
- Select values within a range using `BETWEEN`.
- Search for text patterns using `LIKE`.
- Combine conditions using `AND` and `OR`.
- Sort filtered results using `ORDER BY`.

## 3. Tools and Technologies
- Google Colab
- Python
- SQLite
- SQL
- Pandas

## 4. Dataset Description
Sample data was created for two tables: `Customers` and `Products`.

### Customers Table
| Column | Description |
|---|---|
| CustomerID | Unique customer identifier |
| CustomerName | Customer name |
| City | Customer's city |
| Country | Customer's country |

### Products Table
| Column | Description |
|---|---|
| ProductID | Unique product identifier |
| ProductName | Name of the product |
| Category | Product category |
| Price | Product price |

The sample dataset contains six customer records and eight product records.

## 5. SQL Queries Implemented

1. Filter customers by city using `WHERE`.
2. Find products priced above a specified amount using `>`.
3. Find products priced below a specified amount using `<`.
4. Select customers from specified cities using `IN`.
5. Exclude customers from specified cities using `NOT IN`.
6. Filter products within a price range using `BETWEEN`.
7. Find product names starting with a specified letter using `LIKE`.
8. Find product names ending with a specified letter using `LIKE`.
9. Search product names containing specific text using `LIKE`.
10. Combine category and price conditions using `AND`.
11. Filter products using `OR`.
12. Combine `BETWEEN` and `ORDER BY` to filter and sort products.

## 6. Methodology
1. Imported SQLite and Pandas in Google Colab.
2. Created an in-memory SQLite database.
3. Created the Customers and Products tables.
4. Inserted sample records into both tables.
5. Executed 12 SQL filtering queries.
6. Displayed the results using Pandas DataFrames.
7. Reviewed the outputs to understand how different SQL operators work.

## 7. Key Learnings
- Filtering records with `WHERE`.
- Comparing numeric values using `>` and `<`.
- Matching multiple values using `IN` and `NOT IN`.
- Filtering ranges using `BETWEEN`.
- Searching text patterns using `LIKE` and wildcards.
- Combining conditions using `AND` and `OR`.
- Sorting results using `ORDER BY`.

## 8. Conclusion
This task provided practical experience with SQL filtering techniques. It helped improve my understanding of how to retrieve specific records, apply multiple conditions, search text patterns, and sort filtered data.

## 9. Internship Details
- **Organization:** Veda Technology
- **Task:** SQL Filtering Practice
- **Author:** M. Navya Sri

## 10. Note
This project uses sample customer and product data with SQLite in Google Colab. The internship task lists MySQL and PostgreSQL as tools, but this notebook uses SQLite for practising SQL concepts.
