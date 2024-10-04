# Data Wrangling Project: Dicoding Collection

This repository contains a simple data analysis project focused on practicing **data wrangling** techniques using the DicodingCollection dataset, which is a modified version of the **Shopping Cart Database** from Kaggle.

### Background

Dicoding Collection (DiCo) is a fictional company operating in the fashion industry. They produce various fashion items and sell them through an online platform. The company stores all sales history along with information related to products and customers in a database. As part of the data analysis process, we aim to wrangle and clean this dataset to extract meaningful insights.

### Dataset Description

The dataset consists of four tables:

1. **Customers**: Contains information about customers such as customer_id, customer_name, gender, age, home_address, zip_code, city, state, and country.
   
2. **Orders**: Holds order-related data, including order_id, customer_id, order_date, and delivery_date.

3. **Products**: Provides product details like product_id, product_type, product_name, size, color, price, quantity, and description.

4. **Sales**: Contains sales information with fields like sales_id, order_id, product_id, price_per_unit, quantity, and total_price.

### Objective

The project is divided into several phases to prepare the data for further analysis. These phases are:

1. **Gathering Data**: Collecting all necessary data from the available tables.
   
2. **Assessing Data**: Evaluating the quality and completeness of the data to identify any issues.
   
3. **Cleaning Data**: Handling missing values, correcting data types, and ensuring the dataset is ready for analysis.

### Environment Setup

To run this project, you will need the following libraries:

- `pandas`

We highly recommend using a virtual environment for dependency management to avoid conflicts. You can create a virtual environment using `conda`:

```bash
# Create a new environment
conda create --name dicoding-wrangling python=3.8

# Activate the environment
conda activate dicoding-wrangling

# Install necessary libraries
conda install numpy pandas matplotlib seaborn
```

### Dataset

You can access the dataset [here](https://github.com/dicodingacademy/dicoding_dataset/tree/main/DicodingCollection). 

### Project Steps

1. **Data Gathering**:
   - Load the datasets using `pandas` and merge them to create a comprehensive dataset.

2. **Data Assessing**:
   - Check for missing data, duplicates, and invalid data types.
   - Generate a summary of the dataset.

3. **Data Cleaning**:
   - Fill or remove missing values.
   - Correct any data format issues.
   - Handle outliers and anomalies.
