# E-Commerce Sales Data Cleaning and EDA

This repository contains a Jupyter Notebook that demonstrates the data cleaning and exploratory data analysis (EDA) of an e-commerce platform's sales data for the period from December 2010 to December 2011. The data has been cleaned and processed to extract valuable insights.

## Table of Contents

- [Introduction](#introduction)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Key Findings](#key-findings)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Introduction

E-commerce businesses generate large volumes of data. Understanding and analyzing this data is crucial for making informed business decisions. This repository provides a Jupyter Notebook that walks through the process of cleaning and exploring e-commerce sales data to extract meaningful insights.

## Data Cleaning

In this notebook, we perform the following data cleaning steps:

1. **Data Pruning:** Removing unnecessary columns and information that is not relevant to our analysis.

2. **Handling Missing Data:** Dealing with missing values, which may include removing rows with missing data or imputing values where appropriate.

3. **Adding Useful Information:** Creating new columns, such as total sales by multiplying the unit price and quantity columns. Identifying whether each transaction was a sale or a return based on the sales value.

## Exploratory Data Analysis

The EDA process involves various analyses and visualizations to gain insights into the e-commerce sales data:

1. **Sales by Country:** Analyzing sales data for different countries to identify top-performing regions.

2. **Outlier Detection:** Identifying outliers in sales data, which could indicate unusual or potentially valuable transactions.

3. **New Customers:** Calculating and visualizing the number of new customers added during each month.

4. **Popular Items:** Determining the most popular items by analyzing sales quantities.

5. **Price-Quantity Relationship:** Exploring the relationship between the price of an item and the quantity sold.

6. **Best Sales Seasons:** Identifying the best seasons for sales based on transaction data.

7. **Optimal Advertising Times:** Analyzing the data to determine the best times for placing advertisements to maximize sales.

## Key Findings

The notebook concludes with key findings and insights from the EDA process, which can be used for making data-driven decisions in the e-commerce business.

## Usage

To use this repository, follow these steps:

1. Clone the repository to your local machine.

```bash
git clone https://github.com/your-username/e-commerce-sales-analysis.git
```

2. Ensure you have Jupyter Notebook installed:

```bash
pip install jupyter
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook e-commerce-sales-analysis.ipynb
```

4. Execute the cells in the notebook sequentially to perform data cleaning and exploratory data analysis.

## Dependencies

The following Python libraries are used in this project:

- pandas
- numpy
- matplotlib
- seaborn

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Feel free to explore, modify, and use this repository for your own data analysis projects.

Happy analyzing!
