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

![Image](https://github.com/user-attachments/assets/f90c286b-6ec0-4478-9789-cc5c79ac6408)

### 🔹 b) Removing Duplicates

Using ROW_NUMBER() to identify and remove duplicates:

![Image](https://github.com/user-attachments/assets/21c81391-f5c4-42cf-a771-ad743ecb1b1b)

![Image](https://github.com/user-attachments/assets/dde8a8ac-e4b2-4cd0-8ab0-4d80a7feec10)

![Image](https://github.com/user-attachments/assets/1cd44367-1b5a-4640-b85b-42fee1b3c412)

### 🔹 c) Standardizing Data

- Trimming whitespace from names:

  ![Image](https://github.com/user-attachments/assets/5eea9957-c8cf-4435-8dcf-ef29f42474a2)

 - Converting format:

   ![Image](https://github.com/user-attachments/assets/8564b4b7-7a2f-4661-8ca6-349f1509fd1e)

 - Standardizing values:
   
    ![Image](https://github.com/user-attachments/assets/0a12e88b-8d89-4777-9a27-85db23016bed)
    ![Image](https://github.com/user-attachments/assets/205f5122-3deb-409c-822e-5570c68d9859)

### 🔹 d) Handling Missing Values

- Filling missing values based on existing data:
  
  ![Image](https://github.com/user-attachments/assets/af30f7f5-81b1-491d-b0cf-d1243971ad1e)

- Removing rows where both total_laid_off and percentage_laid_off are missing:

  ![Image](https://github.com/user-attachments/assets/15aa441d-8802-4aef-b150-a84a0b733af3)

### 🔹 e) Dropping Unnecessary Columns

  ![Image](https://github.com/user-attachments/assets/c3e2ed22-1e2c-4c6a-b533-06fe09053a72)

## 📈 2. Exploratory Data Analysis (EDA)

### 📊 a) Summary Statistics

- **Maximum layoffs and percentages:**

  ![Image](https://github.com/user-attachments/assets/1d44bd2f-84cb-467b-acd1-e0dffa656eaa)

- **Date range of layoffs:**

  ![Image](https://github.com/user-attachments/assets/fe1723f2-2410-469f-9402-cfd751134dcf)

 ### 📊 b) Industry & Company Insights

- **Companies with the highest layoffs:**
  
  ![Image](https://github.com/user-attachments/assets/2134edcb-54d4-48ff-b0f9-5ccc6d952ae2)

- **Industries most affected:**
    
    ![Image](https://github.com/user-attachments/assets/847a57e0-a97f-4112-aafb-db0fac33285b)

- **Layoffs by country:**

  ![Image](https://github.com/user-attachments/assets/6d8919b9-fd1f-4db7-bc08-f8b646aaf626)
  
