# Analyzing Sales Data with SQL: Insights for Amazon's E-commerce Platform  

## 📄 Project Overview  
This project involves analyzing Amazon's sales dataset to solve business queries using SQL. The aim is to derive actionable insights related to product pricing, discounts, reviews, and categories to support data-driven decision-making.  

## 📊 Dataset  
The dataset contains detailed information about:  
- Product names  
- Actual and discounted prices  
- Discount percentages  
- Reviews and ratings  
- Product categories  

**Dataset Link**: [Download Here](https://drive.google.com/file/d/1hJOXNpOUXOpyjsrBt1O8MyIJHfWgzakS/view)  

## 🛠 Tools Used  
- SQL Database Environment (e.g., MySQL, PostgreSQL, SQLite)  
- SQL Query Editor (SQL Workbench or any preferred tool)  
- PowerPoint for presentation of findings  

## 🧑‍💻 Problem Statements  
The project addresses the following business queries:  

1. List all products with a discounted price below ₹500.  
2. Find products with a discount percentage of 50% or more.  
3. Retrieve all products where the name contains the word "Cable."  
4. Display the difference between the average actual price and discounted price for each product.  
5. Query reviews mentioning "fast charging" in their content.  
6. Identify products with a discount percentage between 20% and 40%.  
7. Find products priced above ₹1,000 with ratings of 4 stars or higher.  
8. Identify products where the discounted price ends with a 9.  
9. Display review content containing words like "worst," "waste," "poor," or "not good."  
10. List all products where the category includes "Accessories."  

## 📜 Queries  
Here is an example SQL query for one of the problem statements:  

**Problem 1**: List all products with a discounted price below ₹500.  
```sql
SELECT Product_Name, Discounted_Price
FROM Products
WHERE Discounted_Price < 500;
