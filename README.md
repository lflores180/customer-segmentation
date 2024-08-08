# Customer Segmentation Project
## Project Overview

This project utilizes RFM (Recency, Frequency, Monetary) analysis to segment customers of an e-commerce platform. By evaluating how recently and frequently customers make purchases, as well as the monetary value of these purchases, we can classify them into distinct groups. This classification helps in tailoring marketing strategies to different customer segments and enhancing customer engagement.

### Files
- If you do not have the data, please check the etl-pipeline repository first. Find it [here](https://github.com/lflores180/etl-pipeline.git) and follow the steps.
- The Jupyter notebook containing all the scripts, analysis, and visualizations. Find it [here](Customer-Segmentation-Project-Final.ipynb)

### Requirements
- The minimum requirement is Python3
- Import the necessary libraries as [here](requirements.txt)


### Process Overview
### 1. Data Loading and Cleaning:
- The dataset is loaded into a pandas DataFrame.
- Preliminary data cleaning steps, including handling missing values and erroneous entries, are performed.
### 2. Exploratory Data Analysis (EDA):
- Key statistics are derived and visualizations are generated to understand the distribution and trends within the data.
### 3. RFM Analysis:
- Recency: Time since last purchase.
- Frequency: Number of transactions within a fixed period.
- Monetary: Total money spent on purchases.
- Customers are scored based on these metrics to evaluate their engagement level.
### 4. Customer Segmentation:
- Using RFM scores, customers are segmented into categories such as High, Loyal, Regular and Low Spenders.
- Each segment is analyzed in terms of their characteristics and potential business strategies are suggested.
### 5. Visualization:
- The distribution of customers across different segments is visualized.
- Insights are drawn from trends observed in the visual data.
### 6. Strategic Recommendations:
- Based on the segmentation, recommendations are provided on how to approach different customer groups to maximize customer retention and overall sales.

### Installation
1.	Clone the repository, and change the directory to customer-segmentation:

git clone https://github.com/lflores180/customer-segmentation.git

### How to Use
To explore the customer segmentation analysis:
- Open the Jupyter Notebook or JupyterLab [here](Customer-Segmentation-Project-Final.ipynb)
