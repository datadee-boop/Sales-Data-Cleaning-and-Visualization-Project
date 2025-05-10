# 🛍️ Sales Data Cleaning, Analysis & Visualization

## 📋 Table of Contents
- [Project Overview](#project-overview)  
- [Dataset Description](#dataset-description)  
- [Data Cleaning & Preprocessing](#data-cleaning--preprocessing)  
- [Exploratory Data Analysis & Visualizations](#exploratory-data-analysis--visualizations)  
- [Technologies Used](#technologies-used)  
- [Final Results](#final-results)  
- [Author](#author)

---

## 📈 Project Overview  
This repository combines two projects focused on transforming raw sales data into clean, structured formats and extracting valuable insights through analysis and visualizations.

### 🔹 Part 1: Data Cleaning & Preprocessing  
Cleaned and standardized a messy transactional sales dataset to prepare it for analysis and reporting.  
**Key Skills**:
- Data wrangling with `pandas`, `numpy`, and `dateutil`  
- Handling missing data, correcting types, standardizing text  
- Data validation, normalization, and deduplication

### 🔹 Part 2: Data Analysis & Visualization  
Performed exploratory data analysis (EDA) and created visualizations to uncover insights on product sales, customer behavior, and payment methods.  
**Key Skills**:
- EDA and data summarization  
- Time series and categorical analysis  
- Building visual dashboards with `matplotlib` and `seaborn`

---

## 🗂️ Dataset Description  
The dataset includes fictional retail sales transactions with fields such as:

- `Order_ID`: Unique ID for each transaction  
- `Customer_Name`, `Gender`, `Age`, `Email`  
- `Product_Category`, `Product_Name`  
- `Quantity`, `Price_Per_Unit`, `Total_Price`  
- `Order_Date`, `Delivery_Status`  
- `Payment_Method`, `Customer_Region`

---

## 🧹 Data Cleaning & Preprocessing  
Key transformations include:

- **Standardized Names and Genders** (e.g., “m”, “Male”, “MALE” → “Male”)  
- **Filled Missing Ages** with median value  
- **Normalized Product Categories** (case, spacing)  
- **Converted Quantity & Price fields** from text and currency formats to numeric  
- **Parsed Multiple Date Formats** into a uniform format  
- **Validated and Cleaned Emails**  
- **Removed Duplicates** to ensure clean records  

---

## 📊 Exploratory Data Analysis & Visualizations  
A variety of visualizations were created to gain business insights:

- 📦 Revenue by Product Category (bar chart)  
- 📈 Sales Trend Over Time (line plot)  
- 💳 Payment Method Distribution (pie chart)  
- 🌍 Sales by Region (bar chart & boxplot)  
- 🏆 Top Products by Sales (bar chart)  
- 💸 Customer Spending Distribution (histogram)  
- 🔢 Sales vs Quantity Sold (scatter plot)  
- 🔥 Sales Heatmap by Product and Payment Method  
- 🗓️ Weekly Sales Patterns (bar chart by weekday)

---

## 💻 Technologies Used
- **Python**  
- **Pandas** & **NumPy** – data manipulation  
- **Matplotlib** & **Seaborn** – visualizations  
- **Dateutil** – flexible date parsing  

---

## ✅ Final Results  
The final dataset is fully cleaned and analysis-ready. Visualizations provide actionable insights for:

- Product performance  
- Sales trends  
- Customer segmentation  
- Payment behavior

Ideal for stakeholders or BI tools to support decision-making.

---

## 👨‍💻 Author  
**datadee-boop**  
Aspiring Data Analyst passionate about transforming messy data into valuable business insights.  
📧 *Feel free to connect or reach out for feedback or questions!*
