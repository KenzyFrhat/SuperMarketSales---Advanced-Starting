# Supermarket Sales Exploratory Data Analysis

## Project Overview

This project performs Exploratory Data Analysis (EDA) on a supermarket
sales dataset. The goal is to understand customer behavior, product
demand, and sales patterns across different cities, product lines, and
time periods.

## Dataset Description

The dataset contains supermarket transaction records.

-   Rows: 1000 transactions
-   Columns: Multiple features describing customers, products, and
    sales.

Each row represents a **single purchase transaction**.

### Important Features

-   Invoice ID: Unique identifier for each transaction
-   Branch: Store branch
-   City: City where the branch is located
-   Customer type: Member or Normal customer
-   Gender: Customer gender
-   Product line: Category of purchased product
-   Unit price: Price of one item
-   Quantity: Number of items purchased
-   Total: Total purchase value
-   Date / Time: Timestamp of transaction
-   Payment: Payment method
-   Rating: Customer satisfaction score

## EDA Steps

The analysis process included:

1.  Inspecting dataset structure (shape, columns, data types)
2.  Separating categorical and numerical features
3.  Exploring distributions of numerical variables
4.  Detecting derived features and relationships
5.  Time‑based analysis of transactions
6.  Customer behavior analysis by gender
7.  Product line demand across cities


## Visualizations

The project includes several visualizations:

-   Histograms for numerical features
-   Bar charts for categorical comparisons
-   Pivot tables for city vs product line analysis
-   Time‑based transaction analysis

## Key Insights

-   Transactions are relatively balanced across the three cities.
-   Product demand is distributed across several product lines.
-   Customer ratings appear uniformly distributed in the dataset.
-   Some temporal patterns appear across weekdays.

## Tools Used

-   Python
-   Pandas
-   Matplotlib
-   Seaborn
-   Jupyter Notebook

## How to Run the Project

1.  Download the dataset.
2.  Install the required libraries.
3.  Open the Jupyter notebook.
4.  Run the cells to reproduce the analysis.
