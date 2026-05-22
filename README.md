# Amazon Customer Behavioral Analysis

## Project Overview

This project analyzes Amazon customer shopping behavior to understand customer preferences, shopping patterns, and purchasing habits. The goal is to identify useful customer insights that can help improve marketing strategies, customer retention, and personalized recommendations.

---

## Objectives

The project focuses on:

- Customer shopping frequency analysis
- Preferred shopping categories
- Product search/payment preferences
- Device usage behavior
- Customer segmentation based on behavior
- Age vs spending behavior analysis
- Gender vs category preference analysis
- Device type vs purchase frequency analysis
- Customer persona generation
- Marketing insights generation

---

## Dataset Information

Dataset Used:

**Amazon Customer Behavior Survey Dataset**

The dataset contains customer demographic details and shopping behavior information such as:

- Age
- Gender
- Purchase frequency
- Purchase categories
- Product search method
- Browsing behavior
- Customer reviews importance
- Shopping satisfaction
- Recommendation helpfulness
- Cart abandonment behavior

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Collection
The dataset was loaded using Pandas.

### 2. Data Cleaning
The following preprocessing steps were performed:

- Missing value handling
- Empty value replacement
- Duplicate checking
- Data formatting

### 3. Exploratory Data Analysis (EDA)

Customer behavior was analyzed through:

- Shopping frequency distribution
- Preferred category analysis
- Product search preference analysis
- Age-based spending behavior
- Gender category comparison

### 4. Customer Segmentation

Customers were segmented into groups based on:

- Age
- Shopping frequency
- Purchase behavior

Segments generated:

- Young Frequent Buyers
- Young Occasional Buyers
- Mature Frequent Buyers
- Mature Occasional Buyers

### 5. Customer Personas

Behavior-based personas were generated for better marketing understanding.

Example:

**Young Frequent Buyer**
- Shops frequently
- Interested in beauty/fashion products
- Responds well to personalized recommendations

**Mature Occasional Buyer**
- Shops less frequently
- Looks for discounts and loyalty benefits

### 6. Marketing Insights

Key insights discovered:

1. Most customers shop a few times a month.
2. Beauty and Personal Care and Clothing categories are highly preferred.
3. Customers mainly use keyword/product search methods.
4. Younger customers purchase more frequently.
5. Female customers show stronger category preferences.
6. Customer behavior differs significantly across segments.
7. Personalized recommendations work better for young frequent buyers.
8. Discounts and loyalty programs are effective for mature occasional buyers.

---

## Visualizations Generated

### Required Visualizations

1. Shopping Frequency Countplot
2. Payment/Product Search Preference Pie Chart
3. Age vs Spending Boxplot

### Additional Visualizations

4. Heatmap – Gender vs Category Preference
5. Violin Plot – Age vs Spending
6. Customer Segmentation Plot

---

## Project Structure

```text
Amazon-Customer-Behavioral-Analysis/
│── datasets/
│── outputs/
│── plots/
│── report/
│── Amazon_Customer_Behavioral_Analysis.ipynb
│── Amazon_Customer_Behavior_Survey.csv
│── cleaned_dataset.csv
│── README.md
