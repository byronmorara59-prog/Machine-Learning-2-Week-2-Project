## Customer Segmentation (ML Clustering)


#### 1. Project Description

In this project, I use a clustering algorithm to perform customer segmentation on a dataset. Customer segmentation is a common technique used in marketing to divide customers into groups based on similar characteristics, such as purchasing behavior or demographics. By segmenting customers, businesses can gain valuable insights to tailor their marketing strategies, product offerings, and customer service.


#### 2. Problem Statement

The dataset contains relevant features such as customer demographics (birth year, education, marital status, income), transaction history (purchase amounts per product category), and purchasing frequency across different channels. The goal is to segment customers into meaningful groups and understand what makes each group unique.


#### 3. Dataset

Source: Customer Personality Analysis — Kaggle
Size: 2,240 customers, 29 columns
CategoryColumnsDemographicsYear_Birth, Education, Marital_Status, Income, Kidhome, TeenhomeSpending HistoryMntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProdsPurchase FrequencyNumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumDealsPurchasesEngagementRecency, AcceptedCmp1–5, Response, Complain
 

#### 4. ML Workflow

1. Data Cleaning and Preprocessing
2. Feature Engineering
3. Dimensionality Reduction (PCA)
4. K-Means Clustering
5. DBSCAN Clustering
6. Model Evaluation
7. Cluster Interpretation and Visualisation


#### 5. Model Evaluation
- Elbow Method & Silhouette Score (for K-Means): To determine the optimal number of clusters
- Dendrogram Analysis (for Hierarchical Clustering): To analyze the hierarchy of clusters
- Cluster Distribution & Interpretability: Analyzing cluster characteristics to ensure meaningful segmentation
- Visualization: Using t-SNE and PCA to visualize the clusters in 2D space