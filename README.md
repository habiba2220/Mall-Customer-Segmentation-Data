# Mall-Customer-Segmentation-Data
I implemented K-Means clustering to identify distinct customer segments based on spending behavior and income patterns from the Mall Customers dataset.


# Customer Segmentation Analysis

A machine learning project that segments mall customers into distinct groups based on their spending behavior and income using K-Means clustering.

## Project Overview

This project analyzes customer data to identify distinct segments that can inform targeted marketing strategies. Using unsupervised learning techniques, I've grouped customers based on their annual income and spending scores.

## Dataset

The Mall Customers dataset contains information about 200 customers:
- CustomerID: Unique ID for each customer
- Gender: Male or Female
- Age: Customer's age
- Annual Income (k$): Annual income in thousands of dollars
- Spending Score (1-100): Score assigned by the mall based on customer behavior and spending nature

## Methodology

1. **Data Exploration**: Analyzed distributions and relationships between variables
2. **Data Preprocessing**: Selected relevant features and scaled the data
3. **Elbow Method**: Determined the optimal number of clusters (5)
4. **K-Means Clustering**: Implemented clustering algorithm to segment customers
5. **Visualization**: Created scatter plots to visualize the segments
6. **Analysis**: Interpreted each cluster and derived business insights

## Results

Identified 5 distinct customer segments:

1. **Cluster 0**: Medium Income, Medium Spending - The average customer
2. **Cluster 1**: High Income, Low Spending - Conservative spenders
3. **Cluster 2**: Low Income, Low Spending - Budget-conscious customers
4. **Cluster 3**: Low Income, High Spending - Carefree spenders
5. **Cluster 4**: High Income, High Spending - Premium customers

## Business Applications

- Targeted marketing campaigns for each segment
- Personalized product recommendations
- Optimized store layout and product placement
- Improved customer retention strategies
