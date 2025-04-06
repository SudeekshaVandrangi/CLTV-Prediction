## 🔍 CLTV Prediction & Customer Segmentation for Personalized Insurance Policies

A machine learning-driven project designed to predict Customer Lifetime Value (CLTV) and segment insurance customers for tailored policy offerings. This project was developed for Vahan Bima, a motor vehicle insurance provider, using regression and clustering techniques to optimize marketing strategies, boost customer retention, and enhance profitability within the insurance industry.

## 📌 Problem Statement Traditional insurance marketing tends to use a generic approach, resulting in ineffective resource distribution and missed opportunities. Vahan Bima aimed to enhance its offerings by:

Predicting the long-term value (CLTV) of its customers

Segmenting them based on behavioral and demographic data

Customizing products and strategies for high-value and underserved segments

## 🎯 Objectives

Predict Customer Lifetime Value (CLTV) through regression models

Segment customers using predicted CLTV and behavioral features with clustering

Improve marketing efficiency, service personalization, and policy development

## 🛠️ Techniques Used

📊 CLTV Prediction Using Regression Models
Final Model: Gradient Boosting
Compared Models: Linear, Lasso, Ridge, Decision Tree, Random Forest, KNN, Neural Networks

## 📈 Customer Segmentation Using Clustering
Chosen Algorithm: Mini Batch K-Means
Comparison Algorithm: BIRCH
Optimization: Elbow Method for determining optimal K
Evaluation Metrics: SSE, Davies-Bouldin Index

## 🧪 Results

CLTV Prediction R² Score (Test Set): 92.53% (Gradient Boosting)

Optimal Number of Clusters: 3

Top Features: Claim Amount, Vintage, Marital Status

## 📊 Segmentation Insights:

Cluster 0: High CLTV & Claim Amount—ideal for premium products

Cluster 2: Urban-dominant, silver policyholders

Cluster 1: Lower CLTV, cost-sensitive customers

## 📂 Project Structure

regression_model.ipynb: CLTV prediction using various ML models

clustering_model.ipynb: Customer segmentation with K-Means & BIRCH

eda_clusters.ipynb: Exploratory analysis of customer clusters

cltv.csv: Dataset for CLTV prediction

cltv_cleaned.csv: Cleaned dataset for CLTV prediction

cltv_clustered.csv: Dataset after clustering

## 📊 Key Features in Dataset

Demographics: Gender, Area, Marital Status, Qualification

Policy Information: Policy Type, Income Level, Number of Policies

Behavioral Metrics: Vintage (Tenure), Claim Amount

Target Variable: Predicted CLTV (monetary value)

## 💡 Use Cases

1. Targeted marketing campaigns

2. Premium policy offerings for high-value clusters

3. Personalized customer communication for improved retention

4. Better resource allocation across customer segments

## Future Work

Integrate deep learning for more dynamic CLTV predictions

Visualize clusters with interactive dashboards (Power BI/Tableau)

Incorporate geospatial risk factors using GIS data

Scale the system using Apache Hadoop/Spark for big data processing

Authors: 

Sudeeksha Vandrangi, Nayan Bhiwapurkar, Shreyas Hingmire, Vaishnavi Chunchu, Toshal Warke

📄 License This project is open-source and licensed under the MIT License.
