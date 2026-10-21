# Thiranex Internship Tasks

## About This Repository

This repository contains the tasks and projects completed as part of my internship with **Thiranex**. It showcases my practical work, learning progress, and skills in data analytics, data visualization, and machine learning.

## Tasks Completed

### Task 1: Offer Letter Announcement

- Shared the internship offer letter on LinkedIn as instructed.
- Tagged Thiranex in the LinkedIn post.

### Task 2: Sales & Revenue Analysis Dashboard

#### Project Overview

Developed an interactive Sales & Revenue Analysis Dashboard using Microsoft Power BI to analyze sales performance, revenue trends, customer activity, and regional sales patterns.

#### Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)

#### Key Performance Indicators (KPIs)

- Total Sales
- Unique Customers
- Products Sold
- Sales Records
- Total Quantity
- Total Profit

#### Dashboard Features

- Monthly sales trend analysis
- Sales analysis by category
- Top 10 sub-categories by sales
- Regional sales comparison
- Interactive filters and slicers
- KPI cards for tracking business performance

#### Project Objective

The objective of this project was to transform sales data into meaningful visual insights to understand revenue trends, customer activity, product performance, and regional sales distribution.

#### Dashboard Preview

<img width="1303" height="737" alt="Sales & Revenue Analysis Dashboard" src="https://github.com/user-attachments/assets/8c26b5a9-a0b7-46ee-b166-578d5dbc2427" />

### Task 3: Customer Segmentation Using K-Means Clustering

#### Project Overview

Developed a customer segmentation project using Python and machine learning techniques to group customers based on their purchasing behavior. The project uses sales data to identify customer groups with different spending patterns and product preferences.

#### Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

#### Dataset Description

The dataset contains 9,800 sales records and 15 columns, including customer names, product details, categories, regions, order dates, and sales amounts.

#### Methodology

1. Loaded and explored the sales dataset using Pandas.
2. Checked missing values and duplicate records.
3. Aggregated sales data to create customer-level features.
4. Calculated total spending, unique products, sub-category variety, and sales record counts.
5. Standardized numerical features using StandardScaler.
6. Used the Elbow Method to help select the number of clusters.
7. Applied K-Means clustering with three clusters.
8. Visualized customer groups and compared their average spending.

#### Customer Segmentation Results

The model identified three customer clusters:

| Cluster | Number of Customers | Average Spending |
|---|---:|---:|
| Cluster 0 | 294 | 1,133.79 |
| Cluster 1 | 153 | 5,540.16 |
| Cluster 2 | 346 | 3,123.00 |

*Average spending is reported in the dataset's original sales units.*

#### Key Findings

- **Cluster 0 — Lower-Spending Customers:** Customers with the lowest average spending and a smaller variety of purchased products.
- **Cluster 1 — Higher-Spending Customers:** Customers with the highest average spending and the greatest product variety.
- **Cluster 2 — Moderate-Spending Customers:** Customers whose average spending falls between the other two clusters.

These segment labels are interpretations based on the calculated cluster averages.

#### Project Limitations

- The dataset does not contain demographic attributes such as age, gender, or income. Therefore, the analysis focuses on purchasing behavior rather than demographic segmentation.
- The dataset does not contain an Order ID, so sales record counts represent product-level rows rather than distinct orders.
- The clusters describe patterns in the selected features and do not directly measure customer loyalty or future purchase intent.

#### Project Files

- `Customer_Segmentation.ipynb` — Jupyter Notebook containing data analysis, clustering, and visualizations.
- `customer_segments.csv` — Customer-level data with cluster assignments.
- `cluster_summary.csv` — Summary statistics for each cluster.

## Skills Developed

- Data cleaning and preprocessing
- Exploratory data analysis
- Data visualization
- Power BI dashboard development
- DAX measures and calculations
- Customer-level feature engineering
- K-Means clustering and feature scaling
- Interpretation of data-driven business insights
- GitHub project documentation

## Future Tasks

Additional internship tasks and projects will be added to this repository as they are completed.

## Author

MCA Student | Aspiring Data Analyst

---

*This repository showcases my practical learning and project work during the Thiranex internship.*
