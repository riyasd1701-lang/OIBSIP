# Customer Segmentation Analysis Using K-Means Clustering

## Oasis Infobyte Data Analytics Internship

**Level:** 1  
**Task:** 2 – Customer Segmentation Analysis

## Project Overview

This project analyses mall customers and groups them according to annual income and spending score using K-Means clustering.

The purpose is to identify customer segments and explore potential marketing strategies for different groups.

## Dataset

**Dataset:** Mall Customer Segmentation Data  
**Source:** Kaggle  
**Records:** 200  
**Columns:** 5

Dataset link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

The dataset contains:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Technologies Used

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn

## Project Workflow

1. Dataset loading and inspection
2. Data quality checks
3. Exploratory Data Analysis
4. Feature selection and standardisation
5. Elbow Method for cluster selection
6. K-Means clustering
7. Silhouette Score evaluation
8. Cluster visualisation and profiling
9. Business recommendations and conclusion

## Customer Segmentation

Customers are grouped based on their annual income and spending score.

Cluster profiles are analysed using average age, annual income, spending score and customer count.

## Business Recommendations

- Explore premium offers for high-income, high-spending customers.
- Test personalised promotions for high-income, low-spending customers.
- Consider value-based rewards for customers with high spending scores and lower incomes.
- Explore budget-friendly offers for lower-income, lower-spending customers.

These recommendations are exploratory and require further validation.

## How to Run

1. Download the project notebook.
2. Open it in Google Colab.
3. Download the Mall Customers dataset from Kaggle.
4. Upload `Mall_Customers.csv` to Colab.
5. Run the notebook cells in sequence.

## Limitations

The dataset contains only 200 customers and does not include detailed transaction histories. The clustering model uses annual income and spending score rather than actual purchase frequency or transaction value.

## Conclusion

This project demonstrates how K-Means clustering can identify groups of customers with different income and spending characteristics. The resulting segments can support exploratory marketing analysis and customer profiling.
