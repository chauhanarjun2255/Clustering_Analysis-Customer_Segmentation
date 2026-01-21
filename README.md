Task 3: Customer Segmentation using K-Means Clustering

Project Overview
This project performs customer segmentation using K-Means clustering based on
customer purchasing behavior. The goal is to group customers into meaningful segments
to help businesses design targeted marketing strategies and improve decision-making.

Objective
- Segment customers based on demographic and spending behavior
- Identify meaningful customer groups
- Visualize clusters for better understanding
- Provide actionable business insights

Dataset Information
File Name: `Customer_data.csv`
Columns:
- CustomerID– Unique identifier for each customer
- Age– Age of the customer
- AnnualIncome– Annual income of the customer
- SpendingScore– Score representing spending behavior

Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
  - StandardScaler
  - KMeans
  - PCA
  - Silhouette Score
- Jupyter Notebook

Project Workflow

1. Data Loading
- Load the dataset using Pandas
- Inspect structure and sample records

2. Data Preprocessing
- Select relevant numerical features
- Apply StandardScaler to normalize data

3. Finding Optimal Clusters
- Use Elbow Method
- Plot WCSS vs Number of Clusters
- Identify optimal value of K

4. K-Means Clustering
- Apply K-Means with optimal clusters
- Assign cluster labels to customers

5. Visualization
- Reduce dimensions using **PCA**
- Visualize clusters in 2D scatter plot
- Visualize Pair Ploat that give relationships between features within clusters.

Visual Outputs
- Elbow Method plot
- PCA-based cluster visualization
- Cluster-labeled dataset

How to Run the Project

1. Ensure Python is installed
2. Install required libraries: pip install pandas numpy matplotlib seaborn scikit-learn
3. Place sales_data.csv in the project directory 
4. Open and run the Jupyter Notebook step-by-step

