👩🏻‍🎓 Customer Shopping Behavior Analysis | Data Analytics Portfolio Project

This repository contains my **first hands-on Data Analytics portfolio project**, created as part of my learning journey in Data Analytics.  
As a student, my objective was to apply concepts of **Python, SQL, and Power BI** on a real-world dataset and understand how an **end-to-end analytics workflow** is executed in professional environments.

This project focuses on converting raw customer transaction data into meaningful insights that can support business decision-making.

---

## 🎯 Purpose of the Project
The main goals of this project were to:

- Practice real-world **data cleaning and preprocessing**
- Perform **business-oriented data analysis using SQL**
- Build an **interactive Power BI dashboard**
- Learn how to **communicate insights** through reports and visualizations

This project helped me connect theoretical knowledge with practical implementation.

---

## 📌 Project Overview
The dataset contains approximately **3,900 customer purchase records** across multiple product categories.

Through this project, I analyzed:
- Customer demographics and spending behavior
- Subscription vs non-subscription purchasing patterns
- Impact of discounts and shipping types
- Product performance and customer loyalty

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation & Exploratory Data Analysis (Python)
- Loaded and explored the dataset using Pandas
- Checked data types, distributions, and missing values
- Handled missing values in the Review Rating column using **median imputation by category**
- Standardized column names using snake_case
- Performed feature engineering:
  - Created `age_group`
  - Created `purchase_frequency_days`

---

### 2️⃣ Data Analysis Using SQL (PostgreSQL)
After cleaning the data, it was loaded into **PostgreSQL** for structured analysis.

Key analyses performed:
- Revenue analysis by age group and gender
- Subscriber vs non-subscriber spending comparison
- Customer segmentation (New, Returning, Loyal)
- Identification of high-value and discount-dependent products
- Shipping type vs average purchase amount analysis

---

### 3️⃣ Data Visualization (Power BI)
An interactive **Power BI dashboard** was created to present insights such as:
- Revenue distribution across demographics
- Customer segmentation and loyalty
- Product and category performance
- Subscription-based revenue comparison

The dashboard is designed to be easily understandable for non-technical users.

---

### 4️⃣ Reporting & Insights
A detailed project report was prepared that includes:
- Key findings from the analysis
- Business insights derived from the data
- Practical recommendations based on observed trends

---

## 🛠️ Tools & Technologies Used
- **Python:** Pandas, NumPy, Matplotlib
- **SQL:** PostgreSQL
- **BI Tool:** Power BI
- **Environment:** Jupyter Notebook

---

## 🧪 How to Use This Repository

### Clone the Repository
```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

### Python Analysis
Open the notebook:
```
Customer_Shopping_Behavior_Analysis.ipynb
```

This notebook includes:
- Data import and exploration
- Data cleaning and preprocessing
- Feature engineering
- Loading cleaned data into PostgreSQL

---

### SQL Analysis
- Create a PostgreSQL database
- Execute queries from:
```
customer_behavior_sql_queries.sql
```

---

### Power BI Dashboard
- Open:
```
customer_behavior_dashboard.pbix
```
- Connect it to the PostgreSQL database
- Explore interactive visuals

---

## 📚 Key Learnings
- Understanding the complete data analytics lifecycle
- Writing SQL queries for real business problems
- Cleaning and transforming real-world datasets
- Creating dashboards for insight communication
- Integrating Python, SQL, and Power BI in one project

---

## 🔮 Future Improvements
- Add advanced SQL queries (CTEs, window functions)
- Perform predictive analysis
- Improve dashboard interactivity
- Work with larger and more complex datasets

---

⭐ Thank you for taking the time to explore my project.  
Any feedback or suggestions are welcome!
