**#Customer Segmentation Analysis**

This repository contains a data analysis project focused on exploring and visualizing sales data using Python. The analysis includes insights into customer demographics, purchasing behavior, and regional sales patterns derived from the provided dataset.

**#Dataset**

The dataset (SalesData.csv) includes information about sales transactions, including attributes such as:

User ID
Customer Name
Product ID
Gender
Age Group
Age
Marital Status
State
Zone
Occupation
Product Category
Orders
Amount (Sales amount)
The dataset was cleaned to handle missing values and ensure data types are appropriate for analysis. Exploratory data analysis (EDA) techniques were applied to uncover patterns and trends within the dataset.

**#Analysis Highlights**

The analysis covers the following aspects:

Descriptive Statistics: Summary statistics for numerical columns such as age, orders, and sales amount.

![Screenshot 2024-06-26 011308](https://github.com/piyushsharda2803/Salesanalysis/assets/87650893/29bda90f-9dcc-4b65-9133-72df29323b82)

Visualization: Utilization of seaborn and matplotlib for visualizing data distributions and relationships. Key visualizations include:

![download](https://github.com/piyushsharda2803/Salesanalysis/assets/87650893/eaf924f1-9f20-4a05-abde-cb18983eacef)

Count plots for categorical variables (e.g., Gender, Age Group, State).
![download (1)](https://github.com/piyushsharda2803/Salesanalysis/assets/87650893/e50f9d6e-ab21-48db-9a2c-f1081c5c7255)

Bar plots to show total sales by various categories (e.g., Gender, Age Group, State, Occupation, Product Category).
Insights: Derived insights regarding customer demographics, popular product categories, and top-performing regions in terms of sales.

**#Conclusion**

Based on the analysis, the typical buyer profile emerges as married women aged 26-35 from states like Uttar Pradesh, Maharashtra, and Karnataka. These buyers are primarily engaged in sectors such as IT, Healthcare, and Aviation, showing preferences for products in Food, Clothing, and Electronics categories.

**#Repository Structure**

SalesData.csv: Raw dataset used for analysis.
sales_data_analysis.ipynb: Jupyter notebook containing Python code for data cleaning, analysis, and visualization.
README.md: This file providing an overview of the project, dataset, analysis, and conclusions.

**#Dependencies**

Ensure you have the following Python libraries installed to run the notebook:

1. numpy
2. pandas
3. matplotlib
4. seaborn

**#Usage**

To replicate the analysis:
1. Clone this repository to your local machine.
2. Install python and the required dependencies using pip install -r requirements.txt.
3. Open and run sales_data_analysis.ipynb in Jupyter Notebook or JupyterLab.
4. Follow the notebook cells sequentially to see data cleaning steps, exploratory analysis, and visualizations.


Feel free to explore, modify, or extend the analysis further based on your interests or specific business questions.
