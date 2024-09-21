# Empowering Farmers with Data-Driven Solutions

This repository contains the code for analyzing farmer query data collected from Kisan Call Centres (KCC). The project focuses on analyzing queries raised by farmers to gain insights into the challenges faced by them in different regions of India. The data includes attributes such as Sector, Category, Crop, Query Type, State, District, Block, and Submission Time. The analysis helps in automating responses to similar queries in the future, thus improving the efficiency of KCC.

## Features
1. **Data Preprocessing**: The dataset is preprocessed using Python libraries like Pandas and Scikit-learn. This includes:
   - Data cleaning and transformation
   - One-Hot Encoding for categorical data
   - Dimensionality reduction using Principal Component Analysis (PCA)

2. **Attribute Selection**: 
   - A heat map is generated to visualize the correlation.
   - Attributes with a correlation higher than 0.2 are selected for further analysis.

3. **Query Matching**:
   - The system matches new farmer queries to existing queries in the dataset.
   - The solutions provided to previous queries are fetched and presented as solutions for new queries.

## Datasets
- Data was sourced from data.gov.in in CSV format, covering queries from farmers in states like Haryana, Gujarat, Jammu & Kashmir, Tamil Nadu, Uttar Pradesh, and Rajasthan.

## Requirements
- Python 3.7 or above
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib

## Results
- The project successfully reduces the dimensionality of the dataset, retaining key features relevant to query resolution.
- It generates association rules and correlations between attributes, helping to automate query responses for future queries.
