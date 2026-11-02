<img width="1303" height="737" alt="Screenshot 2026-10-18 010849" src="https://github.com/user-attachments/assets/8a8cb233-0a94-46fb-bf89-12d113cae4ed" /># Thiranex Internship Tasks

## About This Repository

This repository contains the tasks and projects completed as part of my internship with **Thiranex**. It showcases my practical work, learning progress, and skills in Data Analytics, Data Visualization, Machine Learning, and Predictive Analytics.

## Tasks Completed

### Task 1: Internship Offer Letter Announcement

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

#### Project File

<img width="1303" height="737" alt="Screenshot 2026-10-18 010849" src="https://github.com/user-attachments/assets/24a86a6b-3b9c-4319-a748-9a4c02a9f3b5" />

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

| Cluster | Number of Customers | Average Spending |
|---|---:|---:|
| Cluster 0 | 294 | 1,133.79 |
| Cluster 1 | 153 | 5,540.16 |
| Cluster 2 | 346 | 3,123.00 |

Average spending is reported in the dataset's original sales units.

#### Key Findings

- **Cluster 0 – Lower-Spending Customers:** Customers with the lowest average spending and a smaller variety of purchased products.
- **Cluster 1 – Higher-Spending Customers:** Customers with the highest average spending and the greatest product variety.
- **Cluster 2 – Moderate-Spending Customers:** Customers whose average spending falls between the other two clusters.

These segment labels are interpretations based on the calculated cluster averages.

#### Project Limitations

- The dataset does not contain demographic attributes such as age, gender, or income. Therefore, the analysis focuses on purchasing behavior rather than demographic segmentation.
- The dataset does not contain an Order ID, so sales record counts represent product-level rows rather than distinct orders.
- The clusters describe patterns in the selected features and do not directly measure customer loyalty or future purchase intent.

#### Project Files

- `Task 3.ipynb` – Jupyter Notebook containing data analysis, clustering, and visualizations.
- `customer_segments.csv` – Customer-level data with cluster assignments.
- `cluster_summary.csv` – Summary statistics for each cluster.


### Task 4: Predictive Analytics – Weekly Sales Forecasting

#### Project Overview

Developed a predictive analytics project using Python and machine learning techniques to analyze historical weekly sales data and forecast future sales.

The project focuses on identifying sales patterns, building predictive models, evaluating their performance, and generating future weekly sales predictions.

#### Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Statsmodels

#### Project Objectives

- Analyze historical weekly sales data.
- Perform data preprocessing and exploratory analysis.
- Build predictive models for weekly sales forecasting.
- Compare different forecasting techniques.
- Evaluate model performance using regression metrics.
- Generate future weekly sales predictions.

#### Methodology

1. Loaded and explored the weekly sales dataset.
2. Performed data preprocessing and prepared the time-series data.
3. Split the data into training and testing sets.
4. Built a Linear Regression model.
5. Developed a Random Forest Regression model.
6. Implemented an ARIMA time-series forecasting model.
7. Evaluated model performance using MAE, RMSE, and R² Score.
8. Generated future weekly sales forecasts.

#### Models Implemented

- **Linear Regression:** Used to establish a baseline predictive model for weekly sales.
- **Random Forest Regression:** Used an ensemble learning approach to predict sales based on patterns in the training data.
- **ARIMA (AutoRegressive Integrated Moving Average):** Used a time-series forecasting approach to predict future weekly sales.

#### Model Evaluation Results

The models were evaluated using the following metrics:

- **MAE (Mean Absolute Error):** Measures the average absolute difference between actual and predicted sales.
- **RMSE (Root Mean Squared Error):** Measures prediction errors while giving greater weight to larger errors.
- **R² Score:** Measures how well the model explains variations in the target variable.

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 69,412.58 | 84,650.61 | -0.0803 |
| Random Forest Regression | 120,120.44 | 140,513.82 | -1.9765 |
| ARIMA | 104,878.25 | 122,601.63 | -1.3684 |

#### Future Sales Forecast

The ARIMA model was also used to generate future weekly sales predictions.

Sample forecast results:

| Date | Predicted Weekly Sales |
|---|---:|
| 2012-11-02 | 1,538,713 |
| 2012-11-09 | 1,556,450 |
| 2012-11-16 | 1,563,433 |
| 2012-11-23 | 1,566,182 |

#### Key Learnings

- Understanding predictive analytics and time-series forecasting.
- Working with historical sales data.
- Building and comparing regression models.
- Understanding ARIMA model implementation.
- Evaluating predictive models using regression metrics.
- Generating future sales forecasts using Python.

#### Project File

- `Task 4.ipynb` – Jupyter Notebook containing data preprocessing, model building, evaluation, and weekly sales forecasting.


## Skills Developed

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Power BI Dashboard Development
- Power Query and DAX
- Python Programming
- Pandas and NumPy
- Machine Learning
- Customer Segmentation
- K-Means Clustering
- Predictive Analytics
- Linear Regression
- Random Forest Regression
- Time-Series Forecasting using ARIMA
- Model Evaluation
- Data Interpretation and Business Insights
- GitHub Project Documentation

## Future Tasks

Additional internship tasks and projects will be added to this repository as they are completed.

## Author

MCA Student | Aspiring Data Analyst

---

This repository showcases my practical learning, technical skills, and project work during the Thiranex internship.
