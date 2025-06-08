# machine_learning_project-unsupervised-learning

## Project Overview
This project applies unsupervised learning techniques to analyze wholesale customer purchasing behaviors. We explore clustering methods and dimensionality reduction to uncover hidden patterns in the data and provide actionable insights.

## Project Objectives
Exploratory Data Analysis (EDA): Understand data distributions, correlations, and spending trends.

K-Means Clustering: Identify distinct customer segments based on purchasing behavior.

Hierarchical Clustering: Visualize customer relationships through a dendrogram to explore natural groupings.

Principal Component Analysis (PCA): Reduce dimensionality to highlight the most influential features affecting customer segmentation.

### Duration:
Approximately 1 hour and 40 minutes

### Project Description:
Exploratory Data Analysis (EDA) & Preprocessing
Import and clean the dataset Handle missing values and detect outliers 
Perform feature scaling using Standardization 
Identify correlations among variables using a heatmap

Unsupervised Learning Models

K-Means Clustering:
Determines optimal number of clusters using the Elbow Method & Silhouette Score
Groups customers into low spenders, mid-range buyers, and bulk purchasers

Hierarchical Clustering:

Applies different linkage methods (Ward’s, Complete, etc.) to assess customer similarity
Dendrogram visualization highlights continuous spending patterns

Principal Component Analysis (PCA):
Reduces feature dimensions while retaining maximum variance
Identifies Grocery, Frozen, and Fresh Products as top contributors

Insights & Business Applications
Feature Importance Analysis:
PCA results suggest Grocery spending dominates customer segmentation
Frozen & Fresh products hold moderate importance, indicating specialized buying behaviors
Milk has minimal impact, meaning it does not significantly differentiate customers

Optimal Clustering Approach:
K-Means clustering showed distinct customer spending behaviors
Hierarchical clustering (Dendrogram) revealed continuous distributions, suggesting segmentation flexibility

Outlier Detection & Specialized Buyers:

Some customers exhibited high spending on Fresh & Frozen goods, likely bulk buyers or food suppliers
These insights help customize pricing strategies, inventory planning, and targeted marketing

Conclusion
This project delivers valuable business insights by:  
Segmenting customers based on their spending habits  
Identifying key features influencing purchasing decisions 
Optimizing marketing strategies based on cluster analysis 
Improving decision-making for wholesalers
