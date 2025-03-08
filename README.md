# Customer Segmentation using R

## Overview
Customer segmentation is the process of dividing a customer base into groups of individuals with similar characteristics. This project uses R to analyze customer data and implement clustering techniques to identify meaningful segments.

## Dataset
- **File:** `Mall_Customers.csv`
- **Columns:**
  - `CustomerID`: Unique customer identifier
  - `Gender`: Male/Female
  - `Age`: Customer age
  - `Annual Income (k$)`: Customer's yearly income
  - `Spending Score (1-100)`: Score assigned based on spending behavior

## Methodology
1. **Data Exploration**
   - Displaying the first few rows
   - Checking for missing values
   - Summary statistics and standard deviation analysis
2. **Data Visualization**
   - Gender distribution
   - Age distribution
   - Income vs. Spending Score plots
3. **Clustering**
   - Using the Elbow method to determine optimal clusters
   - Applying K-means clustering
   - Visualizing cluster results

## Results
- Identified optimal clusters for customer segmentation
- Visualized customer groups based on spending behavior and income

## Visualizations
<img src = "https://github.com/haripatel07/CustomerSegmentationUsingR/blob/main/Visualization1.png" width = "500">
<img src = "https://github.com/haripatel07/CustomerSegmentationUsingR/blob/main/Visualization2.png" width = "500">
<img src = "https://github.com/haripatel07/CustomerSegmentationUsingR/blob/main/Visualization2.png" width = "500">

## Business Insights
- **Gender Analysis:** The dataset shows that female customers are slightly more than male customers, indicating potential targeted marketing strategies for different demographics.
- **Age Distribution:** The majority of customers fall within the 30-35 age group, suggesting that marketing campaigns should focus on this age range.
- **Spending Behavior:** Customers with mid-range annual incomes tend to have higher spending scores, highlighting a key target audience for promotional offers.
- **Cluster Findings:**
  - High-income, high-spending customers form a premium segment, ideal for luxury product marketing.
  - Low-income, low-spending customers represent a budget-conscious segment that may respond well to discounts.
  - Young customers with moderate income and high spending scores indicate an opportunity for trendy and lifestyle-based promotions.

## Dependencies
- R (version 4.0+ recommended)
- Required libraries: `ggplot2`, `dplyr`, `cluster`, `factoextra`

## Usage
1. Install required libraries using `install.packages("package_name")`
2. Run the provided R script or execute the notebook step by step

## Conclusion
This project provides an insightful analysis of customer segmentation, helping businesses target specific customer groups more effectively.

## Author
Hari Patel

