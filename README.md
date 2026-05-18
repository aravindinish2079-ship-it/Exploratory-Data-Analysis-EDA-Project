# Exploratory-Data-Analysis-EDA-Project
# Exploratory Data Analysis (EDA) Project

## Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a laptop dataset using Python data science libraries. The main objective of the project is to clean, preprocess, analyze, and visualize the dataset to discover meaningful patterns, trends, and insights.

The project demonstrates practical data analysis techniques commonly used in real-world data science workflows.

---

## Objectives

* Understand the structure of the dataset
* Handle missing and inconsistent values
* Remove duplicate records
* Detect and analyze outliers
* Perform statistical analysis
* Create visualizations for data interpretation
* Generate actionable insights from the dataset

---

## Dataset Information

The dataset contains laptop-related information such as:

* Company
* Laptop Type
* Screen Size
* Screen Resolution
* CPU
* RAM
* Storage
* GPU
* Operating System
* Weight
* Price

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Google Colab

---

## Data Cleaning & Preprocessing

The following preprocessing techniques were applied:

* Removed unnecessary columns
* Handled missing values
* Replaced invalid symbols such as `?`
* Removed duplicate rows
* Converted datatypes into proper numerical formats
* Cleaned columns such as RAM and Weight
* Detected and handled outliers

---

## Exploratory Data Analysis Performed

The project includes several visual and statistical analyses such as:

* Price distribution analysis
* Laptop brand comparison
* RAM vs Price analysis
* Laptop type distribution
* Correlation heatmaps
* Weight vs Price analysis
* Average price by company
* Outlier detection using boxplots

---

## Key Insights

* Higher RAM laptops generally have higher prices
* Premium laptop brands dominate the high-price segment
* Gaming laptops are typically heavier and more expensive
* Most laptops in the dataset contain 8GB RAM
* Certain outliers significantly affect price distribution

---

## Visualizations Included

* Histogram plots
* Count plots
* Bar charts
* Scatter plots
* Boxplots
* Heatmaps

---

## Project Structure

```text id="x3rjlwm"
EDA-Project/
│
├── README.md
├── notebook.ipynb
├── laptopData.csv
├── cleaned_laptop_data.csv
│
└── images/
    ├── heatmap.png
    ├── price_distribution.png
    ├── ram_vs_price.png
    └── company_analysis.png
```

---

## Future Improvements

* Build machine learning models for price prediction
* Create interactive dashboards using Streamlit or Power BI
* Apply advanced feature engineering techniques
* Perform predictive analytics

---

## Conclusion

This project demonstrates the importance of data cleaning, preprocessing, and visualization in understanding real-world datasets. Through exploratory data analysis, meaningful insights and trends were identified that can support future machine learning and business intelligence applications.
