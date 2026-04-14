# 📊 Online Course Platform – SQL Data Analysis Project

## 📌 Project Overview

This project analyzes learner purchasing behavior for an online course platform using SQL. The goal is to explore relationships between learners, courses, and purchases to generate meaningful business insights.

The analysis focuses on revenue trends, course performance, and learner engagement patterns.

## 🗂 Database Structure

The project uses three main tables:

* **learners** – Contains learner details (learner_id, full_name, country)
* **courses** – Contains course information (course_id, course_name, category, unit_price)
* **purchases** – Contains transaction details (purchase_id, learner_id, course_id, quantity, purchase_date)

## 🔍 Key SQL Concepts Used

* INNER JOIN, LEFT JOIN, RIGHT JOIN
* GROUP BY and HAVING
* Aggregate functions (SUM, COUNT, COUNT DISTINCT)
* Views
* Subqueries
* Filtering using NULL conditions

## 📈 Analytical Questions Solved

1. Display each learner’s total spending along with their country.
2. Identify the top 3 most purchased courses based on total quantity sold.
3. Show each course category’s total revenue and number of unique learners.
4. List learners who purchased courses from more than one category.
5. Identify courses that have not been purchased at all.

## Screen shorts
<img width="972" height="497" alt="image" src="https://github.com/user-attachments/assets/83e43892-1db9-4305-90aa-e99d023cba52" />
<img width="967" height="391" alt="image" src="https://github.com/user-attachments/assets/d1b5eb61-4296-48e5-bd2a-5880d23bf02e" />
<img width="988" height="458" alt="image" src="https://github.com/user-attachments/assets/18754320-a302-4b5e-8cdb-2b42eec80a46" />
<img width="1028" height="396" alt="image" src="https://github.com/user-attachments/assets/bff9db7d-a12e-45a1-a626-82a56428717c" />
<img width="996" height="320" alt="image" src="https://github.com/user-attachments/assets/30b5e999-433c-4972-890e-cee984ec4ed5" />
<img width="946" height="407" alt="image" src="https://github.com/user-attachments/assets/0878a88b-48cc-4276-9ce5-8d73de0120df" />
<img width="1015" height="643" alt="image" src="https://github.com/user-attachments/assets/2a051f27-d91f-4821-a884-5729b560ecd6" />
## 📊 Key Insights

* Revenue is concentrated in a small number of high-performing courses and categories.
* Some learners purchase across multiple categories, indicating strong engagement and higher customer value.
* A few courses show zero purchases, suggesting potential improvement areas in pricing or marketing.
* Learner spending varies significantly, allowing opportunities for customer segmentation.

## 🚀 Business Recommendations

* Focus marketing efforts on top-performing categories to maximize revenue.
* Promote cross-selling strategies to encourage multi-category purchases.
* Review and optimize low-performing courses.
* Identify and reward high-value learners to improve retention.

## 🛠 Tools Used

* MySQL
* SQL Queries
* GitHub for documentation

## 📌 Conclusion

This project demonstrates the practical application of SQL in performing data exploration, aggregation, and business-driven analysis. The insights generated can support strategic decision-making in marketing, pricing, and course development.

