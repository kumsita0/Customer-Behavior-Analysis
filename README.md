# Customer-Behavior-Analysis
Customer Behavior Analysis Using Python

## Project Overview

This project analyzes customer purchasing behavior using Python to identify spending patterns, customer demographics, and purchasing trends. Exploratory Data Analysis (EDA) techniques and visualizations are used to uncover meaningful business insights.

---

## Objective

The objective of this project is to analyze customer purchase data and identify factors influencing customer spending behavior. The project demonstrates data analysis and visualization skills using Python.

---

## Dataset

The dataset contains customer purchasing information, including:

- CustomerID
- Age
- CustomerType
- AnnualIncome
- SpendingScore
  
---

## Data Preparation

The following preprocessing steps were performed:

- Loaded the dataset using Pandas.
- Displayed the first few records of the dataset.
- Examined the dataset structure.
- Reviewed the column names and data types.
- Prepared the dataset for exploratory data analysis.

---

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

---

## Results

The exploratory data analysis revealed several insights into customer purchasing behavior.

### Sample Outputs

#### Age Distribution

<img width="607" height="242" alt="image" src="https://github.com/user-attachments/assets/c4bf10d0-0241-43ea-ab7d-9af6004d33ba" />

#### Histogram of Spending Score

<img width="872" height="596" alt="image" src="https://github.com/user-attachments/assets/47b8514d-2d03-49e3-9fe0-b419eb6d34f3" />

#### Histogram of Annual Income 

<img width="1007" height="611" alt="image" src="https://github.com/user-attachments/assets/41c746e3-b056-4fa0-8c46-483d39211571" />

#### Boxplot of SpendingScore by CustomerType

<img width="1007" height="611" alt="image" src="https://github.com/user-attachments/assets/f8e23d0c-205e-4d69-a7a8-f4a327213697" />

#### Annual Income vs Spending Score Scatter Plot

<img width="912" height="587" alt="image" src="https://github.com/user-attachments/assets/2fd8c0b5-8d4f-4301-84f9-9a5921beb153" />

#### Correlation Heatmap

<img width="667" height="476" alt="image" src="https://github.com/user-attachments/assets/3c14d201-1379-45a3-bf9b-2fbe64bd4b33" />

---

### Summary

- Customer spending behavior varies across different age groups.
- Customers with similar annual incomes can have very different spending scores.
- Exploratory analysis highlights patterns that can support customer segmentation and marketing strategies.

---

## Key Findings

- Customer spending behavior varies across different age groups.
- Spending Score does not always increase with Annual Income.
- Customer demographics reveal differences in purchasing behavior.
- Exploratory visualizations help identify patterns that can support customer segmentation and targeted marketing strategies.

---
## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## How to Run

1. Clone this repository.
2. Install the required packages.

```bash
pip install -r requirements.txt
```

3. Open the notebook in Jupyter Notebook.

4. Run all cells.

---

## Future Improvements

- Perform missing value and duplicate record analysis.
- Build customer segmentation models using clustering.
- Develop predictive models to forecast customer spending.
- Create an interactive dashboard using Power BI or Tableau.

---
## Repository Structure

```text
Customer-Behavior-Analysis/
│
├── customer_behavior_analysis.ipynb        # Main Jupyter Notebook containing Python code for data exploration, statistical analysis, customer segmentation insights, and visualization |
│
├── customer_purchase_behavior.csv          #  Dataset containing customer demographic and purchasing behavior information used for analysis |
│
├── README.md                               # Contains project overview, business objective, dataset information, methodology, visualizations, findings, and project results |
│
├── requirements.txt                        #  Contains required Python packages and dependencies needed to execute the analysis |

