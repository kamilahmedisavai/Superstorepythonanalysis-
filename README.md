Superstore Sales Analysis & Customer Segmentation

Project Overview

This project focuses on analyzing a Superstore Sales Dataset to extract valuable insights about sales performance, customer behavior, and business trends. The analysis includes Exploratory Data Analysis (EDA), predictive modeling, customer segmentation, and advanced visualizations to help businesses make data-driven decisions.

Objectives

Perform Exploratory Data Analysis (EDA) to understand key patterns and trends in sales, profit, and discount structures.

Identify correlations between different sales metrics.

Perform Geographical Analysis to understand regional sales performance.

Use machine learning models to predict sales trends.

Implement Customer Segmentation using K-Means clustering.

Create data visualizations for better insights.

Dataset Information

The dataset consists of sales transactions with the following key attributes:

Ship Mode: Type of delivery service.

Segment: Customer category.

Country, City, State, Region: Geographical details.

Category, Sub-category: Product classification.

Sales, Quantity, Discount, Profit: Transaction details.

Project Structure

Steps Involved

1. Data Preprocessing

Load the dataset and check for missing values.

Handle duplicates and inconsistent data.

Feature engineering for better insights.

2. Exploratory Data Analysis (EDA)

Distribution analysis of sales, profit, and discount.

Correlation analysis to find relationships between features.

Geographical insights using maps to understand sales distribution by location.

3. Outlier Detection

Use Boxplots to detect and handle outliers in sales, profit, and discount.

4. Predictive Modeling

Linear Regression and Decision Trees to predict future sales trends.

Evaluate model performance using MAE, RMSE, and R².

5. Customer Segmentation (K-Means Clustering)

Identify different customer groups based on sales and purchase behavior.

Use Elbow Method to determine the optimal number of clusters.

6. Advanced Visualizations

Heatmaps, Pair plots, and Scatter plots to visualize insights.

Geographical maps to analyze regional sales trends.

7. Deployment (Optional)

Build a simple Streamlit dashboard to interact with predictions.

Deploy using Flask/Django for a web-based application.

Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Geopandas)

Jupyter Notebook for analysis

Machine Learning (Regression, Clustering)

Data Visualization (Seaborn, Matplotlib, Plotly)

Geographical Mapping (Geopandas, Folium)

Installation

Clone the repository:

Install dependencies:

Run the analysis in Jupyter Notebook or execute the main script:

or

Results & Insights

Identified top-performing categories and regions for sales.

Detected that higher discounts lead to lower profit margins.

Found customer segments based on spending behavior.

Developed a predictive model to forecast sales with reasonable accuracy.

Created a geographic sales distribution map.

Future Improvements

Improve predictive modeling using XGBoost or Random Forest.

Add Time-Series Analysis for forecasting trends.

Deploy an interactive dashboard for better user experience.

Contributors

Your Name (your.email@example.com)
