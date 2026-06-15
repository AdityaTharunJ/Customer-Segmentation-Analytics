## Customer Segmentation Analysis using K-Means Clustering

## Project Overview

Customer Segmentation is the process of dividing customers into distinct groups based on their demographic characteristics, lifestyle, and purchasing behavior. This project uses K-Means Clustering to identify meaningful customer segments that can help businesses improve marketing strategies, customer engagement, and decision-making.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, clustering, and interactive dashboard creation using Power BI.

## Objective

The primary objective of this project is to:

Analyze customer demographic and behavioral data.
Group customers into meaningful segments using K-Means Clustering.
Identify characteristics of each customer segment.
Generate business insights and recommendations.
Visualize results through an interactive Power BI dashboard.
Dataset Information

The dataset contains customer information such as:

Feature	Description
Gender	Customer gender
Ever_Married	Marital status
Age	Customer age
Graduated	Graduation status
Profession	Occupation of customer
Work_Experience	Years of work experience
Spending_Score	Spending behavior (Low, Average, High)
Family_Size	Number of family members
Var_1	Additional categorical feature
Segmentation	Existing customer segment label (used only for reference)

## Technologies Used
Python
Pandas
NumPy
Matplotlib
Scikit-Learn
Jupyter Notebook
Power BI

## Project Workflow

1. Data Collection
Imported customer dataset from CSV files.

3. Data Preprocessing
Handled missing values.
Removed unnecessary columns.
Checked data quality and consistency.

4. Exploratory Data Analysis (EDA)
Age distribution analysis.
Spending score analysis.
Family size analysis.
Profession distribution analysis.

5. Feature Engineering
Converted categorical variables using One-Hot Encoding.
Standardized features using StandardScaler.

6. Customer Segmentation
Applied K-Means Clustering.
Determined optimal number of clusters using the Elbow Method.
Assigned cluster labels to customers.

7. Cluster Analysis

Analyzed clusters based on:

Age
Family Size
Work Experience
Spending Behavior
Gender Distribution
Profession Distribution

7. Dashboard Development

Created an interactive Power BI dashboard to visualize:

Customer distribution by cluster
Average age by cluster
Family size by cluster
Work experience by cluster
Spending score distribution
Gender distribution
Profession distribution

## Key Insights
Customer groups exhibit significant differences in age, family size, and spending behavior.
Certain clusters represent younger customers with larger families.
Some segments consist of experienced professionals with higher purchasing potential.
Spending behavior varies significantly across customer groups, enabling targeted marketing strategies.

## Business Recommendations
Design personalized marketing campaigns for each customer segment.
Offer premium services to high-value customer groups.
Create family-oriented promotions for larger households.
Develop targeted engagement strategies for young professionals and senior customers.
Improve customer retention through segment-specific loyalty programs.

## Project Outputs
Cleaned and processed dataset
Customer segmentation model
Clustered customer dataset (customer_segments.csv)
Power BI Dashboard
Business insights and recommendations
