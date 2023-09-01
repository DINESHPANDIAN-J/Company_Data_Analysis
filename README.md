# Company X and Courier Company Data Analysis

This repository contains code for analyzing data from Company X's order reports and data from a courier company. The goal of this analysis is to calculate and compare shipping charges and identify any discrepancies between Company X's calculations and the courier company's billed charges.

## Table of Contents

1. [Introduction](#introduction)
2. [Dependencies](#dependencies)
3. [Data Loading](#data-loading)
4. [Data Preprocessing](#data-preprocessing)
5. [Merging Datasets](#merging-datasets)
6. [Calculations](#calculations)
7. [Result](#result)
8. [Conclusion](#conclusion)

## Introduction

The main objective of this project is to analyze order data from Company X and compare it with the billing data from a courier company. This analysis helps identify any discrepancies in the calculated shipping charges and the charges billed by the courier company.

## Dependencies

Before running the code, make sure you have the following Python libraries installed:

- pandas
- numpy
- seaborn
- matplotlib.pyplot

You can install these libraries using pip:

```bash
pip install pandas numpy seaborn matplotlib
```

## Data Loading

Data from Company X's order reports, SKU master, and the courier company's reports are loaded from Excel files.

## Data Preprocessing

Data preprocessing includes tasks such as handling missing values, renaming columns, and performing calculations to convert weights and calculate charges.

## Merging Datasets

Data from different sources, such as Company X and the courier company, are merged to create a unified dataset for analysis.

## Calculations

Several calculations are performed, including converting weights into kilograms, calculating total prices and weights, and determining weight slabs and charges. The code contains functions to calculate these values based on specific criteria.

## Result

The final result is a DataFrame that includes relevant columns such as AWB number, weights, delivery zones, expected charges as per Company X, charges billed by the courier company, and the difference between expected and billed charges.

## Conclusion

This analysis helps identify any discrepancies in shipping charges between Company X's calculations and the courier company's billed charges. The results are saved in an Excel file named "result.xlsx" for further analysis or reporting.

Feel free to modify and use this code for your own projects or further analysis.

---

You can use this README as documentation for your code repository, providing a clear overview of the project, its dependencies, and the steps involved in data preprocessing, calculations, and result reporting. It's essential for helping others understand and use your code effectively.
