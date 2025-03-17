# 📊 SQL Data Cleaning & Exploratory Data Analysis (EDA) on Layoffs Data

## 🚀 Introduction

Layoffs have significant implications for businesses, employees, and the broader economy. Analyzing layoffs data can help identify trends, affected industries, and possible reasons behind workforce reductions.

This project focuses on cleaning and analyzing a dataset of layoffs using SQL. The dataset includes information about layoffs from various companies, industries, and locations. The goal is to:

- Clean the data by removing duplicates, standardizing formats, and handling missing values.

- Perform exploratory data analysis (EDA) to extract meaningful insights.

- Identify trends and patterns to understand the impact of layoffs on industries and economies.

By leveraging SQL, I ensure efficient data management and accurate analysis.

## 🛠️ 1. Data Cleaning

### 🔹 a) Creating a Duplicate Table

To preserve the original dataset, a duplicate table (layoffs_staging) is created:

![Image](https://github.com/user-attachments/assets/a3ee5a50-bb82-4fb6-ab8a-89b6c850f271)

### 🔹 b) Removing Duplicates

Using ROW_NUMBER() to identify and remove duplicates:

![Image](https://github.com/user-attachments/assets/21c81391-f5c4-42cf-a771-ad743ecb1b1b)

![Image](https://github.com/user-attachments/assets/dde8a8ac-e4b2-4cd0-8ab0-4d80a7feec10)

![Image](https://github.com/user-attachments/assets/1cd44367-1b5a-4640-b85b-42fee1b3c412)

### 🔹 c) Standardizing Data

- Trimming whitespace from names:

  ![Image](https://github.com/user-attachments/assets/dff46479-87c7-4abd-8667-d38e966d7753)

 - Converting format:

   ![Image](https://github.com/user-attachments/assets/0efde0c3-ee1b-4b67-9664-5055d66b8ebe)

   
  
