# 🛍️ Sales Transactions Data Cleaning and Preprocessing

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Cleaning and Preprocessing Steps](#cleaning-and-preprocessing-steps)
- [Technologies Used](#technologies-used)
- [Final Result](#final-result)
- [Author](#author)

## 📈 Project Overview

Welcome to the **Sales Transactions Data Cleaning and Preprocessing** project! 🚀

In this project, I cleaned and preprocessed a messy sales transactions dataset using Python. The goal was to transform inconsistent, missing, and incorrect data into a clean, structured format ready for analysis. 🧹✨

### Key Skills Demonstrated:
- Data cleaning and preprocessing with **pandas**, **numpy**, and **dateutil**
- Handling missing values 🔄
- Standardizing text data (names, categories, emails) ✍️
- Correcting data types (dates, integers, floats) 🔢
- Removing duplicate records 🚫
- Applying data validation and normalization techniques ⚙️

## 🗂️ Dataset Description

This dataset contains fictional sales transaction records with the following columns:

- **Order_ID**: Unique order identifier 🎫
- **Customer_Name**: Name of the customer (inconsistent formatting) 👤
- **Gender**: Customer gender (various abbreviations and spellings) 👥
- **Age**: Customer age (missing values present) 🎂
- **Product_Category**: Product category (inconsistent casing and spelling) 🏷️
- **Quantity**: Quantity of items purchased (some written as words) 🛒
- **Price_Per_Unit**: Price per item (mixed formats, currency symbols) 💰
- **Total_Price**: Total price of purchase (some non-numeric entries) 💵
- **Purchase_Date**: Date of purchase (various formats) 📅
- **Delivery_Status**: Delivery status (inconsistent text) 📦
- **Email**: Customer email address (missing or incorrectly formatted emails) 📧

## 🧹 Cleaning and Preprocessing Steps

Here’s a breakdown of the steps I took to clean the data:

### ✅ Customer Name
- **What I did**: Stripped spaces and standardized capitalization (e.g., "john doe" → "John Doe"). ✨

### ✅ Gender
- **What I did**: Mapped various entries ("M", "male", "f", "Female") into standardized "Male" and "Female" categories. 👩‍🦱👨‍🦱

### ✅ Age
- **What I did**: Filled missing age values using the median age of the dataset. 🎯

### ✅ Product Category
- **What I did**: Cleaned up inconsistencies in casing and spacing (e.g., "ELECTRONICS" → "Electronics"). 💻

### ✅ Quantity
- **What I did**: Converted quantities written as words ("three") into numeric values. 🔢

### ✅ Price Per Unit
- **What I did**: Removed currency symbols and ensured numeric format. 💲

### ✅ Total Price
- **What I did**: Converted non-numeric total price entries (e.g., "five hundred") into numeric values. 💳

### ✅ Purchase Date
- **What I did**: Parsed and standardized different date formats into consistent date objects. 📅

### ✅ Delivery Status
- **What I did**: Standardized delivery status entries (e.g., "delivered", "Delivered" → "Delivered"). 🚚

### ✅ Email
- **What I did**: Stripped spaces, validated email formatting, and replaced invalid emails with NaN. 📧

### ✅ Duplicates
- **What I did**: Removed duplicate rows based on all columns except the **Order_ID**. 🛑

## 💻 Technologies Used

- **Python** 🐍
- **Pandas** 🧑‍💻
- **NumPy** 🔢
- **Matplotlib** 📊
- **Dateutil** (for flexible date parsing) 📅

## 📊 Final Result

After cleaning and preprocessing the dataset, it is now fully structured, standardized, and ready for:

- **Exploratory Data Analysis (EDA)** 🔍
- **Data visualization** 📈
- **Machine learning** 🤖
- **Business intelligence reporting** 📊

## 👨‍💻 Author

**datadee-boop** 🚀  
Aspiring Data Analyst passionate about turning messy data into valuable insights. 💡  
Feel free to reach out if you have any questions or feedback! 😊
