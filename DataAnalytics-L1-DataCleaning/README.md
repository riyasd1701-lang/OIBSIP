# Data Cleaning and Preprocessing – Snitch Fashion Sales

**Oasis Infobyte Data Analytics Internship**  
**Level 1 – Task 3: Data Cleaning and Preprocessing**

## Project Overview

This project focuses on identifying and correcting data quality issues in the Snitch Fashion Sales dataset using Python. The dataset contains retail transaction information, including customer details, product categories, quantities sold, prices, discounts, sales amounts and profits.

The objective is to improve data consistency, handle missing information, identify invalid values and prepare the dataset for further analysis.

## Dataset Information

- **Dataset:** Snitch Fashion Sales – Uncleaned
- **Original Records:** 2,500
- **Original Columns:** 12
- **Missing Values Before Cleaning:** 5,594
- **Duplicate Records:** 0

### Dataset Attributes

Order_ID, Customer_Name, Product_Category, Product_Name, Units_Sold, Unit_Price, Discount_%, Sales_Amount, Order_Date, City, Segment and Profit.

## Project Objectives

- Identify missing values, duplicate records and inconsistent data.
- Handle missing numerical and categorical information.
- Standardise text formatting and convert date values.
- Detect invalid discount values.
- Identify potential outliers using statistical techniques.
- Compare data quality before and after preprocessing.
- Export the processed dataset for further analysis.

## Tools and Technologies

- **Python:** Data processing and analysis
- **Pandas:** Data manipulation and cleaning
- **NumPy:** Numerical operations
- **Matplotlib:** Data visualisation
- **Seaborn:** Statistical plots
- **Google Colab:** Development environment

## Data Cleaning Process

### 1. Data Inspection

The dataset was examined using Pandas to understand its structure, data types, missing values and duplicate records.

The initial inspection identified 5,594 missing values across Units_Sold, Unit_Price, Discount_%, Order_Date and Segment.

### 2. Missing Value Treatment

Missing numerical values in Units_Sold and Unit_Price were replaced using median imputation.

Missing customer segments were labelled Unknown. Missing order dates were preserved because their original values could not be reliably recovered.

### 3. Discount Validation

The Discount_% column contained fractional values ranging from 0.00 to 1.30.

Assuming discounts are represented as fractions between 0 and 1, 189 observed values exceeding 1.00 were identified as invalid.

Missing and invalid discounts were treated using the median of valid observations.

### 4. Data Formatting

Unnecessary whitespace was removed from text columns, and inconsistent city names were standardised.

The Order_Date column was converted into datetime format to support date-based analysis.

### 5. Outlier Detection

The Interquartile Range (IQR) method was used to identify potential outliers in Units_Sold, Unit_Price, Sales_Amount and Profit.

Potential outliers were flagged and retained because unusual values may represent genuine transactions.

### 6. Data Quality Comparison

The original and processed datasets were compared to evaluate improvements in missing values, formatting and data consistency.

## Project Results

| Metric | Before Cleaning | After Cleaning |
|---|---:|---:|
| Total Records | 2,500 | 2,500 |
| Total Columns | 12 | 20 |
| Missing Values | 5,594 | 606 |
| Duplicate Records | 0 | 0 |
| Missing Order Dates | 606 | 606 |

**Key Findings:**

- Missing values decreased by approximately **89.2%**.
- All 2,500 records were retained.
- Eight additional indicator columns were introduced.
- No exact duplicate records were identified.
- All remaining 606 missing values occur in Order_Date.
- A total of 189 observed discount values were flagged as invalid under the assumed fractional discount range.

## Visualisations

The project includes:

- Outlier detection box plots for numerical attributes.
- Missing-value comparison before and after cleaning.
- Data quality summary tables.

The visualisations are included in the notebook and screenshots document.

## Project Files

```text
DataAnalytics-L1-DataCleaning/
│
├── OIBSIP_DataAnalytics_L1_Task3_DataCleaning.ipynb
├── Snitch_Fashion_Sales_Uncleaned.csv
├── Snitch_Fashion_Sales_Cleaned.csv
├── Screenshots.docx
└── README.md
```

## How to Run the Project

1. Download the Jupyter notebook and original CSV dataset.
2. Open Google Colab.
3. Upload the notebook and dataset.
4. Update the dataset path if necessary.
5. Run the notebook cells sequentially.
6. Review the cleaning results and visualisations.
7. Download the generated cleaned CSV file.

### Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

## Conclusion

The project demonstrates a structured approach to cleaning retail sales data using Python. The preprocessing workflow reduced missing values from 5,594 to 606 while preserving all 2,500 records.

Missing numerical and categorical information was addressed, text formatting was standardised, and invalid discount values and potential outliers were identified.

The resulting dataset provides a more consistent foundation for retail sales analysis. However, the remaining missing dates and estimated numerical values should be considered when interpreting future results.

## Limitations

- The cleaned dataset retains 606 missing order dates.
- Median imputation produces estimates rather than actual transaction values.
- Missing customer segments could not be independently verified.
- Discount validation assumes values are stored as fractional percentages.
- Potential outliers were identified statistically but not verified against original transaction records.

## Future Scope

Future work could include advanced missing-value treatment, automated data validation, transaction verification and further analysis of sales trends, product performance and profitability.

## Internship Details

**Organisation:** Oasis Infobyte  
**Internship Domain:** Data Analytics  
**Level:** 1  
**Task:** 3 – Data Cleaning and Preprocessing

## Author

**Riya Dubey**

GitHub Repository: https://github.com/riyasd1701-lang/OIBSIP
