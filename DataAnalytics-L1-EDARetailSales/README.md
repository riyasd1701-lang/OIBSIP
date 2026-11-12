# Retail Sales Data Analysis

**Oasis Infobyte Internship | Data Analytics | Level 1 – Task 1**

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a retail sales dataset to understand sales performance, customer demographics, purchasing patterns and relationships between numerical variables.

The analysis was completed using Python in Google Colab as part of the Oasis Infobyte Data Analytics Internship.

## Objectives

- Inspect the retail sales dataset and assess data quality.
- Calculate descriptive statistics for numerical variables.
- Analyse monthly and quarterly sales trends.
- Compare revenue across product categories.
- Study customer demographics based on age and gender.
- Examine relationships between numerical variables.
- Visualise transaction amount distributions.
- Develop practical business recommendations based on the findings.

## Dataset Description

The dataset contains 1,000 retail transactions and 9 original columns.

| Column | Description |
|---|---|
| Transaction ID | Unique identifier for each transaction |
| Date | Date of the transaction |
| Customer ID | Customer identifier |
| Gender | Customer gender |
| Age | Customer age |
| Product Category | Product category |
| Quantity | Number of units purchased |
| Price per Unit | Price of each unit |
| Total Amount | Total transaction value |

The dataset contains no missing values or duplicate records.

## Tools and Technologies

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Analysis Performed

1. Data loading and inspection
2. Missing-value and duplicate analysis
3. Descriptive statistical analysis
4. Monthly sales analysis
5. Quarterly sales analysis
6. Product category revenue analysis
7. Customer gender distribution
8. Customer age-group analysis
9. Correlation heatmap
10. Transaction amount distribution using box plots

## Key Findings

- **Total Revenue:** 456,000
- **Highest-Revenue Category:** Electronics – 156,905
- **Highest Sales Month:** May – 53,150
- **Lowest Sales Month:** September – 23,620
- **Highest Sales Quarter:** Q4 – 126,190
- **Lowest Sales Quarter:** Q3 – 96,045
- **Highest-Revenue Age Group:** 46–55 years – 100,690
- **Gender Distribution:** Female 51%, Male 49% of transactions

## Business Recommendations

1. Maintain suitable inventory levels for high-revenue categories, particularly Electronics and Clothing.
2. Investigate the decline in sales during September and Q3.
3. Explore targeted marketing opportunities for customers aged 46–55.
4. Review the performance of Beauty products to identify opportunities for improvement.
5. Use transaction patterns to support pricing, promotional and inventory decisions.

## How to Run the Project

1. Download the Jupyter Notebook file from this repository.
2. Open Google Colab or Jupyter Notebook.
3. Install the required Python libraries if necessary.
4. Upload the retail sales CSV dataset.
5. Update the dataset file path in the notebook if required.
6. Run all notebook cells in sequence.
7. View the generated statistics, charts and observations.

## Project Files

- `OIBSIP_DataAnalytics_L1_Task1_RetailSalesEDA.ipynb` – Main notebook containing Python code, analysis and visualisations.
- `README.md` – Project documentation.
- `screenshots/` – Saved charts and analysis screenshots, when uploaded.

## Limitations

The dataset does not contain individual product names or product identifiers, so the top 10 individual best-selling products cannot be identified. The analysis covers transactions from 2023 and does not establish causal relationships or predict future sales.

## Conclusion

The project demonstrates how Python-based exploratory data analysis can be used to identify retail sales patterns and understand customer purchasing behaviour. The findings provide a basis for improving business planning, inventory management and marketing strategies.

## Internship Details

**Organisation:** Oasis Infobyte  
**Domain:** Data Analytics  
**Level:** Level 1  
**Task:** Exploratory Data Analysis on Retail Sales Data
