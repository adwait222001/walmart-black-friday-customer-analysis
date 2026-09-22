# Walmart Black Friday Customer Analysis

## Project Overview

This project analyzes customer purchase behavior using the Walmart Black Friday sales dataset. The analysis focuses on understanding purchasing patterns across customer demographics, occupations, marital status, city categories, product categories, and years of stay in the current city.

The project also applies statistical techniques such as **Two-Way ANOVA** and the **Central Limit Theorem (CLT)** to investigate differences in purchase amounts and relationships between customer characteristics.

## Business Objective

The objective of this case study is to analyze Walmart customer purchasing behavior and identify meaningful patterns across different customer segments.

The analysis covers:

* Customer and dataset characteristics
* Purchasing patterns across city categories
* Product-category spending
* Occupation-wise spending
* Marital-status spending
* Spending based on years of stay in the current city
* Gender and age-group analysis
* Married vs. single customer comparisons
* Gender and product-category effects on purchase amount
* Occupation and years-of-stay effects on purchase amount
* Sampling distributions using the Central Limit Theorem
* Confidence interval analysis
* Purchase distribution by gender
* Mean, median, and outlier analysis

## Dataset

The analysis uses the **Walmart Black Friday customer purchase dataset**.

The dataset contains customer demographic and purchase-related information, including:

* User ID
* Product ID
* Gender
* Age
* Occupation
* City Category
* Stay in Current City Years
* Marital Status
* Product Category
* Purchase Amount

Additional categorical columns were created during data preparation to make the analysis easier to interpret.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Jupyter Notebook / Google Colab
* GitHub

## Statistical Analysis

### Two-Way ANOVA

Two-Way ANOVA was used to investigate:

1. The effect of occupation category and years of stay in the current city on purchase amount.
2. The effect of gender and product category on purchase amount.
3. The interaction effects between the corresponding variables.

### Central Limit Theorem

The Central Limit Theorem was applied using repeated bootstrap samples to examine sampling distributions of mean purchase amounts across:

* Male and female customers
* Married and single customers
* Different age groups
* Stay in current city comparisons

95% confidence intervals were calculated for the relevant sample means.

### Distribution and Outlier Analysis

The project also examines purchase distributions using boxplots and calculates:

* Mean
* Median
* Standard deviation
* Quartiles
* Interquartile range
* Lower and upper bounds
* Number of outliers

## Project Structure

```text
Walmart_Black_Friday_Customer_Analysis/
│
├── Walmart_Black_Friday_Customer_Analysis.ipynb
├── walmart_data.csv
├── Walmart_Case_Study.pdf
└── README.md
```

## Files

### `Walmart_Black_Friday_Customer_Analysis.ipynb`

Contains the complete Python analysis, including:

* Data loading and preparation
* Exploratory analysis
* Grouped analysis
* Visualizations
* ANOVA tests
* Central Limit Theorem analysis
* Confidence intervals
* Distribution analysis
* Outlier analysis

### `walmart_data.csv`

The dataset used for the analysis.

### `Walmart_Case_Study.pdf`

The completed case-study report containing the questions, analysis, code, outputs, insights, and recommendations.

## Key Findings

The analysis identified differences in customer spending across cities, occupations, product categories, genders, age groups, marital status, and years of stay in the current city.

The ANOVA analysis identified statistically significant effects and interaction effects for the factors examined in the case study.

The CLT analysis was used to compare sample means and confidence intervals across customer groups.

Detailed numerical results, tables, visualizations, and interpretations are available in the notebook and the accompanying PDF report.

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/adwait222001/walmart-black-friday-customer-analysis.git
```

### 2. Open the notebook

Open:

```text
Walmart_Black_Friday_Customer_
```
