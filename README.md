# Customer-Behavior-Analysis
Customer Behavior Analysis Using Python

## Project Overview

This project analyzes customer purchasing behavior using Python to identify spending patterns, customer demographics, and purchasing trends. Exploratory Data Analysis (EDA) techniques and visualizations are used to uncover meaningful business insights.

-----

## Objective

The objective of this project is to analyze customer purchase data and identify factors influencing customer spending behavior. The project demonstrates data analysis and visualization skills using Python.

-----

## Dataset

The dataset contains customer purchasing information, including:

- CustomerID
- Age
- CustomerType
- AnnualIncome
- SpendingScore
  
-----

## Data Preparation

The following preprocessing steps were performed:

- Loaded the dataset using Pandas.
- Displayed the first few records of the dataset.
- Examined the dataset structure.
- Reviewed the column names and data types.
- Prepared the dataset for exploratory data analysis.

-----

## Exploratory Data Analysis

The following analyses were performed:

- Generated summary statistics for the dataset.
- Analyzed the distribution of customer ages.
- Explored the relationship between Age and Spending Score.
- Examined customer demographics based on Customer Type.
- Investigated the relationship between Annual Income and Spending Score.
- Relationship between AnnualIncome and SpendingScore
  
-----

## Visualizations

Visualizations created include:

- Histograms
- Bar Charts
- Scatter Plots
- Correlation Heatmap

-----
## Results

The exploratory data analysis revealed several insights into customer purchasing behavior.

### Sample Outputs

#### Age Distribution

![Age Distribution](images/age_distribution.png)

#### Age vs Spending Score

![Age vs Spending Score](images/age_vs_spending_score.png)

#### Annual Income vs Spending Score

![Annual Income vs Spending Score](images/income_vs_spending.png)

#### Correlation Heatmap

![Correlation Heatmap](images/correlation_heatmap.png)

### Summary

- Customer spending behavior varies across different age groups.
- Customers with similar annual incomes can have very different spending scores.
- Exploratory analysis highlights patterns that can support customer segmentation and marketing strategies.

-----

## Key Findings

- Customer spending behavior varies across different age groups.
- Spending Score does not always increase with Annual Income.
- Customer demographics reveal differences in purchasing behavior.
- Exploratory visualizations help identify patterns that can support customer segmentation and targeted marketing strategies.

-----

## Repository Structure

Customer-Behavior-Analysis/
│
├── customer_behavior_analysis.ipynb
├── customer_purchase_behavior.csv
├── requirements.txt
├── README.md
└── images/
    ├── age_distribution.png
    ├── age_vs_spending_score.png
    ├── income_vs_spending.png
    └── correlation_heatmap.png

-----

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

-----

## How to Run

1. Clone this repository.
2. Install the required packages.

```bash
pip install -r requirements.txt
```

3. Open the notebook in Jupyter Notebook.

4. Run all cells.

-----

## Future Improvements

- Perform missing value and duplicate record analysis.
- Build customer segmentation models using clustering.
- Develop predictive models to forecast customer spending.
- Create an interactive dashboard using Power BI or Tableau.

-----
