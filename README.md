# 🛍️ Customer Shopping Behavior Analysis

## 🔍 Project Overview
This project performs an in-depth **data analytics and business intelligence analysis** on customer shopping transactions to identify purchasing patterns, customer segments, and revenue drivers.

The analysis follows a complete **end-to-end data analytics pipeline**, starting from raw data cleaning to SQL-based business queries and interactive visualization using Power BI.

---

## 🗂️ Dataset Overview
- **Total Records:** ~3,900 transactions  
- **Total Features:** 18 columns  

### Data Includes:
- **Customer Attributes:** Age, Gender, Location, Subscription Status  
- **Transaction Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Behavioral Metrics:** Discount Applied, Review Rating, Shipping Type, Purchase Frequency  

📌 *Missing values were present only in the Review Rating column.*

---

## 🧹 Data Cleaning & Preprocessing (Python)
Performed using **Pandas** in Jupyter Notebook.

### Key Steps:
- Inspected schema and data types using `info()`  
- Statistical overview using `describe()`  
- Handled missing values using **median imputation by product category**  
- Standardized column names using `snake_case`  
- Removed redundant features after logical validation  
- Created new features:
  - `age_group`
  - `purchase_frequency_days`

The cleaned dataset was then exported for SQL-based analysis.

---

## 🧠 Exploratory Data Analysis (EDA)
EDA focused on understanding:
- Distribution of purchase amounts  
- Impact of age and gender on spending  
- Discount usage patterns  
- Customer purchase frequency  

Visual and statistical techniques were used to identify trends and anomalies.

---

## 🗄️ SQL Analysis (PostgreSQL)
The cleaned dataset was loaded into **PostgreSQL** to perform structured business analysis.

### Key SQL Queries:
- Revenue contribution by gender and age group  
- Subscriber vs non-subscriber spending comparison  
- Identification of high-spending discount users  
- Top-rated products based on average reviews  
- Shipping type vs average purchase value  
- Customer segmentation into:
  - New  
  - Returning  
  - Loyal  

SQL queries were optimized for readability and business interpretation.

---

## 📊 Power BI Dashboard
An interactive **Power BI dashboard** was built to communicate insights effectively.

### Dashboard Highlights:
- Revenue distribution by customer demographics  
- Customer segmentation overview  
- Product category performance  
- Subscription-based revenue comparison  
- Discount and shipping impact analysis  

📌 *The dashboard is designed for non-technical stakeholders.*

---

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib  
- **SQL:** PostgreSQL  
- **BI Tool:** Power BI  
- **Environment:** Jupyter Notebook  

---

## 🎯 Key Technical Learnings
- Building scalable data cleaning pipelines  
- Writing business-driven SQL queries  
- Transforming raw data into analytical datasets  
- Creating insight-focused dashboards  
- Understanding how analytics supports business decisions  

---

## 🚀 Future Scope
- Predictive modeling on customer purchasing behavior  
- Advanced SQL analytics (CTEs, window functions)  
- Automated data pipelines  
- Enhanced dashboard interactivity  
