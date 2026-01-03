# E-Commerce-Data-Engineering-Analysis-with-PySpark
Project Overview
This project demonstrates advanced data engineering and modeling techniques using PySpark on a large-scale e-commerce dataset. The primary goal is to provide high-quality data models and strategic reports to support product decision-making processes.

Despite data constraints, I implemented a robust abstraction layer to deliver complex categorical insights.

🛠 Technical Stack
Big Data Framework: Apache Spark (PySpark)

Language: Python

Data Processing: SQL Queries & Window Functions

Visualization: Matplotlib & Pandas

Environment: Google Colab / Cloud Infrastructure

📁 Data Source
The analysis is based on the Brazilian E-Commerce Public Dataset by Olist.

Dataset Link: Kaggle - Olist E-Commerce Dataset

Verification: This project ensures data quality and validation across multiple relational tables.

⚙️ Core Features & SQL Logic
The project focuses on complex business logic through the following technical implementations:

Window Functions: Utilized RANK() partitioned by product_category_name to identify top-tier products.

Data Modeling: Integrated order_items and products datasets to create a unified analytical view.

Optimization: Applied schema inference and categorical filtering to maintain high-performance data processing.

Sample Business Query:
SQL

SELECT 
    product_category_name AS category, 
    product_id AS product_id, 
    price AS unit_price, 
    category_rank AS rank_within_category
FROM product_rankings
ORDER BY category ASC, rank_within_category ASC
📊 Business Insights
Revenue Analysis: Identified the top 10 categories contributing to the majority of the platform's revenue.

Product Strategy: Provided ranked lists of the most valuable products per category to assist in inventory and pricing decisions.

🎯 Alignment with Bybit Requirements
This repository serves as a portfolio piece for the Data Engineer role, showcasing:

High-Quality Python Scripts: Clean, modular, and well-documented PySpark code.
Project Overview
This project demonstrates advanced data engineering and modeling techniques using PySpark on a large-scale e-commerce dataset. The primary goal is to provide high-quality data models and strategic reports to support product decision-making processes.

Despite data constraints, I implemented a robust abstraction layer to deliver complex categorical insights.

🛠 Technical Stack
Big Data Framework: Apache Spark (PySpark)

Language: Python

Data Processing: SQL Queries & Window Functions

Visualization: Matplotlib & Pandas

Environment: Google Colab / Cloud Infrastructure

📁 Data Source
The analysis is based on the Brazilian E-Commerce Public Dataset by Olist.

Dataset Link: Kaggle - Olist E-Commerce Dataset

Verification: This project ensures data quality and validation across multiple relational tables.

⚙️ Core Features & SQL Logic
The project focuses on complex business logic through the following technical implementations:

Window Functions: Utilized RANK() partitioned by product_category_name to identify top-tier products.

Data Modeling: Integrated order_items and products datasets to create a unified analytical view.

Optimization: Applied schema inference and categorical filtering to maintain high-performance data processing.

Sample Business Query:
SQL

SELECT 
    product_category_name AS category, 
    product_id AS product_id, 
    price AS unit_price, 
    category_rank AS rank_within_category
FROM product_rankings
ORDER BY category ASC, rank_within_category ASC
📊 Business Insights
Revenue Analysis: Identified the top 10 categories contributing to the majority of the platform's revenue.

Product Strategy: Provided ranked lists of the most valuable products per category to assist in inventory and pricing decisions.

🎯 Alignment with Bybit Requirements
This repository serves as a portfolio piece for the Data Engineer role, showcasing:

High-Quality Python Scripts: Clean, modular, and well-documented PySpark code.

Complex Querying: Expert-level SQL skills including advanced Windowing.

Logical Thinking: Ability to solve data-path and missing-file issues through logical abstraction.

Global Standards: All documentation and code follow international business standards for cross-team collaboration.

Complex Querying: Expert-level SQL skills including advanced Windowing.


Logical Thinking: Ability to solve data-path and missing-file issues through logical abstraction.

Global Standards: All documentation and code follow international business standards for cross-team collaboration.
