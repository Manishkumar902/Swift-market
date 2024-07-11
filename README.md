# Hey, Welcome 
### This is My Swift Market Project 😊

# Swift Market MySQL Database
![image](https://cdn1.expresscomputer.in/wp-content/uploads/2023/01/04165947/EC_Retail_ECommerce_750.jpg)


## Overview
This project aims to analyze e-commerce sales data stored in a MySQL database. Using Jupyter Notebook, we perform SQL queries to extract insights from the data and visualize them using charts and graphs.

## Features
- Data querying with MYSQL in Jupyter Notebook.
- Data visualization using charts and graphs.
- Insights gained from the analysis.

## Technologies Used
- MySQL for database management.
- Jupyter Notebook for data analysis and visualization.
- Matplotlib and Seaborn for creating visualizations.

## Installation and Setup
To set up the project environment:

- Install MySQL and Jupyter Notebook.
- Install required Python libraries:
```
import os

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns
import mysql.connector
from dotenv import load_dotenv
```

- Configure database connection details in Jupyter Notebook.


## Data Exploration
The dataset contains information about e-commerce sales, including customer details. Here's a sample of the records:

| CustomerID | FirstName | LastName | Email       | Phone  | Address | State |
|---------|------------|-----------|-------------------|------------|----------|-------|
| 1001    | Mahika	|Sunder|	MahikaSunder_11@zmail.com	|03412176590	|H.No. 155, Chana|	Assam   |
| 1002    | Zeeshan	|Vasa|	ZeeshanVasa_1@zmail.com	|+911151051656|	52, Roy Nagar|	Tripura|
...

## Query Examples
Example SQL query to find total sales by product category:
```
SELECT ProductCategory, SUM(Price * Quantity) AS TotalSales
FROM Products
GROUP BY ProductCategory;
```

## Data Visualization
Visualizing total sales by product category using a bar chart:

![image](https://github.com/Deepak-karmiyal/SwiftMarket-mysql-project/assets/139327222/16e350cf-a322-4568-9e64-dcdd7312102d)

##  Results and Insights
* According to the data, the best-selling product category is pet supplies and accessories.
* Bihar has the biggest number of customers.
* March and May have the highest sales growth rate.
* Dora-Aggarwal and Agate-Kalita are the suppliers with the highest sales volume.
* Goa and Bihar generated the highest revenue.

## Contact Information
For any inquiries or collaborations, feel free to reach out to Karmiyaldeepak010@gmail.com.