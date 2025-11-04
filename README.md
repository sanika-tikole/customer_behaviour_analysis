## Customer Shopping Behavior Analysis

This repository contains a complete data analytics project analyzing the "Customer Shopping Behavior" dataset. The project covers the full end-to-end data lifecycle, from raw data ingestion and SQL warehousing to in-depth exploratory data analysis (EDA) in Python and final visualization in a Power BI dashboard.

## 1. Project Overview

The primary goal of this project is to analyze a dataset of 3,900 customer purchases to understand shopping habits and identify key trends. By examining demographics, purchase patterns, and product preferences, the project aims to deliver actionable insights that can help inform business strategy, marketing campaigns, and customer retention efforts.

The project demonstrates skills in:

Data Loading and Cleaning (Python Pandas)

Data Warehousing and Querying (MySQL)

Exploratory Data Analysis (Python, Pandas, Matplotlib, Seaborn)

Business Intelligence & Dashboarding (Power BI)

Reporting & Presentation (PDF, Gamma)

## 2. Dataset

Source: customer_shopping_behavior.csv

Size: 3,900 rows × 18 columns

Description: The dataset includes customer demographics (Age, Gender, Location), purchase details (Item Purchased, Category, Purchase Amount), and behavioral data (Review Rating, Subscription Status, Payment Method, Frequency of Purchases).

Data Quality: Initial analysis revealed 37 missing values in the Review Rating column, which were handled during the data cleaning phase.

## 3. Tools Used

Programming Language: Python

Python Libraries: Pandas (for data manipulation), SQLAlchemy (for database connection), PyMySQL (MySQL driver), Matplotlib/Seaborn (for visualization).

Database: MySQL

Business Intelligence: Power BI Desktop

Presentation: Gamma AI

IDE: Jupyter Notebook

## 4. Project Steps

Data Loading & Warehousing:

Loaded the customer_shopping_behavior.csv into a Pandas DataFrame.

Established a connection to a local MySQL server using SQLAlchemy.

Uploaded the clean DataFrame into a new SQL table (e.g., customer_analysis.mytable) to serve as a data warehouse.

SQL Analysis:

Performed initial analysis and segmentation directly in the database using SQL queries.

Answered key business questions (e.g., total revenue by category, most popular payment methods, customer counts by location) to validate the data.

Exploratory Data Analysis (EDA):

Used the customer_analysis.ipynb Jupyter Notebook for a deep-dive analysis.

Visualized data distributions (e.g., Age, Purchase Amount).

Analyzed categorical data (e.g., Category vs. Gender).

Investigated correlations between variables like Review Rating and Subscription Status.

Dashboard Creation:

Connected Power BI Desktop (customer_analysis.pbix) to the MySQL database.

Built an interactive dashboard to visualize key performance indicators (KPIs) and trends.

The dashboard allows for dynamic filtering by subscription status, gender, category, and shipping type.

Reporting & Presentation:

Summarized all findings into a formal PDF report (Customer Shopping Behavior Analysis (1).pdf).

Created a high-level presentation outline (Customer_Shopping_Behavior_Presentation.md) for a stakeholder presentation using Gamma.

## 5. Dashboard & Report Highlights

The interactive Power BI dashboard provides a consolidated view of key metrics.

Key KPIs:

Total Customers: 3.9K

Average Purchase Amount: $59.76

Average Review Rating: 3.75

Key Visualizations:

% of Customers by Subscription Status: (73% No, 27% Yes)

Revenue by Category: Clothing is the top category, followed by Accessories.

Revenue by Age Group: "Young Adult" (18-25) is the highest-contributing age group.

Sales by Category & Gender: Shows different preferences between male and female customers.

The final PDF report details these findings and provides business recommendations.

## 6. Key Results & Insights

Subscription Opportunity: The majority of customers (73%) are not subscribed, representing a significant opportunity for a targeted subscription-driving campaign.

Demographic Focus: Young Adults (18-25) are the most valuable segment in terms of total revenue. Marketing efforts could be tailored to this group.

Top Category: 'Clothing' is the most dominant category, suggesting it's the core of the business. 'Accessories' is a strong secondary category.

## Visulaization
<img width="1513" height="839" alt="image" src="https://github.com/user-attachments/assets/2735e5ee-3081-4551-a8c0-d8f5087019c7" />

