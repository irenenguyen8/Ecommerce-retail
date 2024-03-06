# RFM Customer Segmentation Analysis

## Overview

This project implements RFM (Recency – Frequency – Monetary) Analysis to segment SuperStore's customer base for targeted marketing campaigns. It assists the Marketing Department in identifying customer groups based on their transaction history and value, facilitating personalized marketing strategies.

## Context

SuperStore is a global retail company aiming to express gratitude to loyal customers and explore potential new ones during the festive season. The Marketing Department seeks assistance from the Data Analysis team to implement RFM segmentation due to the large volume of customer data.

## Key Components

- **Data Preparation**: Dataset preparation suitable for RFM analysis.
- **RFM Calculation**: Calculation of Recency, Frequency, and Monetary scores for each customer.
- **Scoring Method**: Implementation of a scoring method using quintiles.
- **Customer Segmentation**: Grouping customers based on RFM scores.
- **Visualization**: Visualization of customer segments.
- **Analysis and Recommendations**: Providing insights and recommendations for marketing strategies.
- **Index Importance**: Advice on prioritizing RFM indices for SuperStore's retail model.

## Data

This project utilizes a transnational dataset containing all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail. The dataset includes the following fields:

- **InvoiceNo**: Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'C', it indicates a cancellation.
- **StockCode**: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
- **Description**: Product (item) name. Nominal.
- **Quantity**: The quantities of each product (item) per transaction. Numeric.
- **InvoiceDate**: Invoice Date and time. Numeric, the day and time when each transaction was generated.
- **UnitPrice**: Unit price. Numeric, Product price per unit in sterling.
- **CustomerID**: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
- **Country**: Country name. Nominal, the name of the country where each customer resides.

Please note that due to its size, the dataset is not included in the repository. You can obtain the dataset from the dataset dicrectory.

## Results

Results of the analysis, including visualizations and recommendations, can be found in the results/ directory.

# Dependencies

The following dependencies are required to run this project:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook (optional, for running the analysis notebooks)
