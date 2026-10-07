# 🥛 Milk Quality Analysis – Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project focuses on **Exploratory Data Analysis (EDA) of milk quality data** to understand the factors associated with different milk quality grades — **High, Medium, and Low**.

The dataset contains **8,500 milk samples and 13 features**, including chemical, physical, and sensory characteristics such as pH, temperature, fat, protein, lactose, turbidity, taste, odor, and conductivity.

The main goal of this project is to **clean the data, explore patterns, identify relationships between variables, and generate meaningful insights about milk quality**.

---

## 🎯 Objectives

- Explore and understand the milk quality dataset
- Identify and handle missing values
- Check for duplicate records
- Verify appropriate data types
- Identify potential outliers
- Perform Univariate, Bivariate, and Multivariate Analysis
- Study relationships between important variables
- Identify factors associated with milk quality grades

---

## 🧹 Data Cleaning & Preprocessing

The following steps were performed:

- Checked missing values in each column
- Checked for duplicate records
- Filled missing numerical values using **median imputation**
- Checked and confirmed appropriate data types
- Used box plots to inspect unusual or extreme values

Missing values were present in 8 out of 13 columns, and all missing values were less than 1% of the total dataset.

---

## 📊 Exploratory Data Analysis

### 1. Univariate Analysis

Analyzed individual variables using histograms and distribution plots.

Key observations:

- Taste scores were mainly concentrated around 5 and 7.
- Protein and fat percentages showed clustered distributions.
- Odor scores were distributed across the 1–9 range.

### 2. Bivariate Analysis

Explored relationships between two variables using bar plots and scatter plots.

Key findings:

- Higher-quality milk tends to have slightly higher **pH and fat percentage**.
- **Fat_Content_% and Fat_Percentage** showed a clear upward relationship.
- Protein and lactose showed no strong visible relationship.
- High-quality milk samples were more concentrated around higher taste scores.

### 3. Multivariate Analysis

A **correlation heatmap** was used to study relationships between multiple numerical variables.

Important observations:

- Fat % and Protein % → **+0.55**
- pH and Fat % → **+0.52**
- Temperature and Fat % → **-0.52**
- pH and Temperature → **-0.41**

---

## 🔎 Key Insights

- **Fat percentage and protein percentage** showed the strongest positive correlation among the selected variables.
- **pH, Fat Percentage, and Taste Score** showed noticeable patterns across Low, Medium, and High quality grades.
- Taste scores were generally higher for high-quality milk samples.
- Data visualization helped identify patterns and relationships that were difficult to observe from raw data.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset Information

| Information | Details |
|---|---|
| Domain | Milk Quality Analytics |
| Total Records | 8,500 |
| Total Features | 13 |
| Target Variable | `Quality_Grade` |
| Quality Categories | High, Medium, Low |

### Main Features

- pH
- Temperature_C
- Fat_Content_%
- Turbidity
- Color_Value
- Taste_Score
- Odor_Score
- Fat_Percentage
- Turbidity_NTU
- Protein_%
- Lactose_%
- Conductivity_mS
- Quality_Grade

---

## 📈 Conclusion

This project provided practical experience with the complete **Exploratory Data Analysis workflow**, from data cleaning and preprocessing to visualization and insight generation.

It helped demonstrate how data analysis can be used to understand milk quality characteristics and identify relationships between different chemical, physical, and sensory measurements.

---

## 👩‍💻 Author

**Vaishnavi Surwase**

Data Science Student

**Innomatics Research Labs**

---

## ⭐ Project Highlights

- 8,500+ Milk Samples
- 13 Features
- Data Cleaning & Preprocessing
- Missing Value Handling
- Outlier Analysis
- Univariate Analysis
- Bivariate Analysis
- Multivariate Analysis
- Correlation Heatmap
- Data Visualization
- Insight Generation

#DataScience #EDA #Python #Pandas #DataVisualization #DataAnalytics
