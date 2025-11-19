# customer_behavior_analysis

# 📌 Overview

This project analyzes customer shopping behavior using Python, SQL, and Power BI.The goal is to understand patterns in customer purchases, identify top-performing categories/products, and create meaningful insights through visual dashboards.

The project covers:

• Loading and exploring the dataset in Python

• Data cleaning and preprocessing

• Running SQL queries on MySQL

• Building an interactive Power BI dashboard

• Creating a final business insights report


# 📁 Dataset

• Name: Customer Shopping Behavior

• Format: CSV

• Rows: ~4,000

• Columns: Category, Item Purchased, Gender, Age, Price, Purchase Date, etc.

• Source: Public dataset

The dataset includes customer demographics, product categories, and purchase information, allowing both exploratory and business-focused analysis.


# 🛠️ Tools & Technologies

• Python (Pandas, NumPy) – EDA & cleaning

• MySQL + SQLAlchemy – Querying & database operations

• Power BI – Dashboard creation

• Jupyter Notebook / VS Code – Development environment

# 🧪 Project Steps
**1. Data Loading**

• Imported the CSV dataset using Pandas

• Displayed initial rows, checked column types, and validated dataset structure

**2. Exploratory Data Analysis (EDA)**

• Performed descriptive statistics

• Analyzed customer demographics

• Identified most purchased categories & products

• Visualized trends (age groups, price distribution, gender split, etc.)

**3. Data Cleaning**

• Removed duplicates

• Handled missing values

• Converted datatypes (dates, numeric columns)

• Added engineered features like age groups, purchase month, etc.

**4. SQL Analysis (MySQL)**

• Loaded cleaned data into MySQL using SQLAlchemy

• Executed SQL queries such as:

• Total orders by category

• Top products per category

• Revenue by month

• Gender-wise purchase behavior

• Verified results and compared with Python outputs

**5. Power BI Dashboard**

• Created an interactive dashboard featuring:

• Category-wise total sales

• Top products

• Gender and age group insights

• Monthly purchase trends

• KPIs (Total Customers, Total Revenue, Total Orders)

**6. Report Creation**

•A business insights report summarizing:

• Key findings

• Customer behavior trends

• Top categories/products

• Actionable recommendations for decision-making

# 📊 Dashboard Preview

The Power BI dashboard includes:

Slicers for category, gender, and age group

Interactive visuals

Trend charts and product performance views

(Include screenshots in your repo if available.)

# 📝 Results & Insights

• Identified top revenue-generating categories

• Found top 3 most purchased items per category

• Analyzed demographic trends (age, gender preferences)

• Observed seasonal/monthly purchase patterns

• Delivered actionable insights for marketing and product teams

# ▶️ How to Run This Project
**Requirements**

• Install necessary Python packages:

```bash
pip install pandas numpy sqlalchemy pymysql

**Steps:**

• Clone the repository

• Open the Jupyter Notebook / Python script

• Load the dataset

• Run the EDA and cleaning cells

• Set up MySQL, create a database, and update connection details

• Run SQL queries

• Open the Power BI file (.pbix) to explore the dashboard
