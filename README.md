# 2. Customer Data Analysis Projects

## Overview

This repository contains two foundational projects focusing on customer data cleaning, exploration, and segmentation. The aim is to build a strong foundation in data preprocessing, exploratory data analysis (EDA), and insight generation. These projects are designed as stepping stones for more advanced analyses and predictive modeling.

---

## Projects

### **1. Customer Shopping Data Cleaning and Initial Insights**

#### **Description**
This project focuses on cleaning and preparing a dataset containing customer shopping transactions from various malls. The dataset includes demographic, purchase, and payment information for nearly 100,000 customers.

#### **Objectives**
- Clean the dataset by handling missing values, duplicates, and inconsistencies.
- Standardize categorical data and convert date columns into a usable format.
- Summarize key numerical variables using statistical measures such as mean, median, and variance.

#### **Key Outcomes**
- Dataset reduced to **94,433 unique rows** after cleaning.
- Statistical summaries provided insights into customer demographics and spending patterns.
- Price distribution showed significant outliers, indicating high-value transactions in specific categories (e.g., Shoes).

#### **Next Steps**
The cleaned dataset will be used for advanced exploratory data analysis (EDA) and modeling in subsequent projects.

---

### **2. Customer Segmentation Data: EDA**

#### **Description**
This project builds on a cleaned customer segmentation dataset, exploring patterns, trends, and relationships among customer groups. The dataset contains demographic, behavioral, and preference information for over 53,000 customers.

#### **Objectives**
- Analyze the distribution of income levels and customer segmentation groups.
- Investigate relationships between numerical features such as `Age`, `Income Level`, and `Coverage Amount`.
- Visualize patterns using histograms, KDE plots, hexbin plots, pairplots, and boxplots.
- Assess correlations between features to understand dependencies.

#### **Key Outcomes**
- **Income Distribution**:
  - Customers fall into distinct income brackets, with peaks around **$40,000**, **$100,000**, and **$120,000**.
- **Segmentation Insights**:
  - Segment 5 represents the largest customer base, while Segment 3 and Segment 1 are the smallest.
  - Income levels across segments show minimal variation, suggesting segmentation is influenced by multiple factors.
- **Feature Relationships**:
  - Age and income show minimal correlation, indicating segmentation may depend on behavioral or demographic attributes.
- **Age Groups**:
  - Income levels remain consistent across age bins (e.g., 18–30, 30–40) across all segmentation groups.

#### **Next Steps**
Future analyses will focus on:
1. **Advanced Clustering**: Using machine learning techniques to refine segmentation.
2. **Behavioral Insights**: Examining how interaction types, preferences, and other behavioral data drive segmentation.
3. **Predictive Modeling**: Building models to predict segmentation groups or customer preferences.

---

## Tools and Libraries

- **Python**: For data cleaning, analysis, and visualization.
- **Libraries**:
  - `Pandas` and `NumPy`: Data manipulation and statistical analysis.
  - `Matplotlib` and `Seaborn`: Data visualization.
  - `scikit-learn`: Encoding categorical data and potential clustering in future projects.

---

## File Structure

- **`project_1/cleaned_customer_shopping_data.csv`**: Cleaned dataset from Project 1.
- **`project_2/cleaned_customer_segmentation_data.csv`**: Cleaned dataset from Project 2.
- **`scripts/`**: Contains Python scripts for data cleaning and analysis.
- **`visualizations/`**: Saved plots and visualizations for insights.

---

## Author Z.S

These projects are part of a learning journey in data analysis and customer segmentation. They showcase fundamental skills in data cleaning, exploratory analysis, and visualization.

---

## Next Steps

- Clustering and predictive modeling to the segmentation dataset.
- Exploratory analysis with advanced techniques.
- Insights to simulate real-world business scenarios, such as marketing campaigns or product recommendations.
