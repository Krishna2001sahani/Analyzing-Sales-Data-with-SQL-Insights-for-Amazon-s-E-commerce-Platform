# 📊 Amazon Sales Data Analysis  

This project demonstrates the use of SQL to analyze sales data for Amazon, solving real-world business problems related to product pricing, discounts, and customer reviews.  

---

## 🚀 Project Objectives  

1. To utilize SQL for extracting actionable insights from e-commerce data.  
2. To address specific business queries provided by management.  
3. To present findings in a structured and visually appealing format.  

---

## 📂 Dataset Details  

The dataset contains:  
- Product names, prices, discounts, and categories.  
- Customer reviews and ratings.  

**Dataset Link**: [Download Here](https://drive.google.com/file/d/1hJOXNpOUXOpyjsrBt1O8MyIJHfWgzakS/view)  

---

## 🔍 Problem Statements  

This project answers the following key business questions:  

1. List all products with a discounted price below ₹500.  
2. Identify products with a discount percentage of 50% or more.  
3. Retrieve products where the name includes "Cable."  
4. Calculate the average price difference between actual and discounted prices.  
5. Query reviews mentioning "fast charging."  
6. Find products with discount percentages between 20% and 40%.  
7. Identify products priced above ₹1,000 with a rating of 4 stars or more.  
8. List products where the discounted price ends with a 9.  
9. Extract reviews with negative sentiments (e.g., "worst," "waste," "poor," "not good").  
10. Retrieve products categorized as "Accessories."  

---

## 🛠 Tools & Technologies  

- **SQL**: Core language for data extraction and analysis.  
- **Database Tool**: MySQL, PostgreSQL, or any preferred environment.  
- **Presentation**: PowerPoint for visually presenting the results.  

---

## 🧑‍💻 Sample SQL Query  

Here’s an example query for one of the problems:  

**Problem**: List all products with a discounted price below ₹500.  
```sql
SELECT Product_Name, Discounted_Price
FROM Products
WHERE Discounted_Price < 500;
