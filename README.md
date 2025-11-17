# Customer Behaviour Analysis – Data Analytics Project

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-00758F?style=flat&logo=sql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=power-bi&logoColor=black)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

## 📌 Project Overview
This repository contains an end-to-end data analytics project focused on **customer shopping behavior**.  
The project uses **Python** for data cleaning and preprocessing, **SQL** for exploratory analysis, and **Power BI** for interactive dashboards to uncover actionable insights.

**Objective:**  
Analyze a dataset of 3,900 customer transactions to understand purchasing patterns, segment valuable customers, and provide recommendations for marketing, sales, and inventory management.

---

## 📂 Dataset
The dataset contains detailed information about customer transactions, including demographics, purchase details, subscription status, and shipping preferences.

**Sample Columns**
- `CustomerID` – Unique identifier for each customer  
- `Age` – Customer age  
- `Gender` – Customer gender  
- `Item Purchased` – Name of purchased item  
- `Category` – Product category (e.g., Clothing, Accessories)  
- `Purchase Amount (USD)` – Transaction value  
- `Location` – Customer location  
- `Size` – Product size  
- `Color` – Product color  
- `Season` – Season of purchase  
- `Review Rating` – Customer review rating  
- `Subscription Status` – Whether the customer is a subscriber  
- `Shipping Type` – Type of shipping chosen  
- `Discount Applied` – Whether discount was applied  
- `Promo Code Used` – Promo code usage  
- `Previous Purchases` – Count of previous purchases  
- `Payment Method` – Payment mode  
- `Frequency of Purchases` – Purchase frequency  

*(Dataset file: `customer_shopping_behavior.csv`)*

---

## 🛠 Tools & Technologies
- **Python**: Pandas, NumPy, Matplotlib, Seaborn  
- **SQL Databases**: PostgreSQL / MySQL / SQL Server  
- **SQLAlchemy**: Database connectivity  
- **Power BI**: Interactive dashboard  
- **Jupyter Notebook / VS Code**: Development environment  
- **Git & GitHub**: Version control  

---

## 📘 Project Workflow

### **1. Data Loading & Preprocessing (Python)**
- Load the dataset using Pandas  
- Inspect data types, missing values, and duplicates  
- Generate summary statistics  
- Feature engineering (e.g., Age Groups, Revenue Metrics)  
- Cleaned data is loaded into **PostgreSQL** via SQLAlchemy  

### **2. Exploratory Data Analysis (EDA)**
- Distribution analysis of purchase amounts  
- Category-level revenue analysis  
- Customer segmentation by age, gender, subscription status  
- Visualizations using **Matplotlib** and **Seaborn**  

### **3. SQL Analysis**
The cleaned dataset is analyzed using SQL queries (`customer_behaviour_analysis.sql`) to uncover business insights:

- Top revenue-generating products and categories  
- Customer segmentation: New, Returning, Loyal  
- Impact of discounts and subscription status on revenue  
- Shipping preferences and satisfaction analysis  
- Age group and demographic behavior analysis  

### **4. Power BI Dashboard**
An interactive **Power BI dashboard** was created to present insights:

**Key KPIs & Insights:**
- Total Customers: 3,900  
- Total Revenue: $233K  
- Average Purchase Amount: $59.76  
- Average Review Rating: 3.75  
- Top Product Categories: Clothing and Accessories  
- Subscriber Analysis: 27% of customers, higher average spend  
- Top Customer Segment: Young Adults  
- Shipping Preferences: Free Shipping and 2-Day Shipping are most popular  

**Dashboard Features:**
- Interactive filters: Gender, Age Group, Category, Subscription, Shipping Type  
- Revenue & sales analysis by category, age group, and subscription status  

<p align="center">
  <img src="customer_behaviour_analysis_dashboard.png" alt="Customer Behaviour Analysis Dashboard" width="800">
</p>

---

## 🚀 How to Use This Project

### **1. Setup Database**
1. Create a PostgreSQL database (e.g., `customer_behavior`)  
2. Update database connection in `Customer_Shopping_Behaviour_Analysis.ipynb`  

### **2. Run Python Notebook**
- Execute cells in `Customer_Shopping_Behaviour_Analysis.ipynb`  
- Load, clean, and preprocess data  
- Push cleaned data to PostgreSQL  

### **3. Run SQL Queries**
- Connect using PgAdmin, DBeaver, or any SQL client  
- Execute queries in `customer_behaviour_analysis.sql`  

### **4. Power BI Dashboard**
- Open `customer_behaviour_analysis.pbix` in Power BI Desktop  
- Connect to your PostgreSQL database and update credentials  
- Explore interactive visualizations and KPIs  

---

## 📈 Key Insights
- **Top Categories:** Clothing and Accessories dominate revenue  
- **High-Value Segment:** Young Adults contribute most to purchases  
- **Subscribers vs Non-Subscribers:** Subscribers spend more and are more loyal  
- **Shipping Preferences:** Free Shipping & 2-Day Shipping lead to higher satisfaction  
- **Purchase Behavior:** Average purchase ~$59–$60, Average review rating ~3.75  

---

## 📁 Repository Structure
├── .gitignore
├── customer_shopping_behavior.csv # Raw dataset
├── Customer_Shopping_Behaviour_Analysis.ipynb # Python notebook for ETL
├── customer_behaviour_analysis.sql # SQL exploratory queries
├── customer_behaviour_analysis.pbix # Power BI project file
├── customer_behaviour_analysis_dashboard.png # Exported dashboard image
└── README.md # Project documentation


---

## 📌 Conclusion
This project demonstrates an **end-to-end data analytics workflow**, integrating **Python, SQL, and Power BI** to analyze customer purchasing behavior. The insights derived can help businesses improve **marketing strategies, inventory planning, and customer retention**.

---

## 📫 Connect / Contact
- GitHub: [https://github.com/msahid-cse](https://github.com/msahid-cse)  
- LinkedIn: [https://www.linkedin.com/in/msahid-cse/](https://www.linkedin.com/in/msahid-cse/)
-  Website: [https://msahid-cse.github.io/portfolio/](https://msahid-cse.github.io/portfolio/)

