# 🔍 PCA & Clustering on USArrests Dataset

## 📊 Overview
This project explores the USArrests dataset using unsupervised machine learning techniques to identify underlying patterns and similarities among U.S. states based on crime statistics. The analysis demonstrates the use of Principal Component Analysis (PCA) for dimensionality reduction and clustering algorithms to group states with similar characteristics.

## 🎯 Project Tasks
- Create a Jupyter Notebook named `unsupervised_task.ipynb`
- Load and explore the `UsArrests.csv` dataset
- Conduct data preprocessing, including normalization and justification of each step
- Perform a correlation analysis and interpret the relationships between features
- Execute PCA to reduce dimensionality and visualize the results through a biplot of the first two principal components
- Select and justify the optimal number of principal components for further analysis
- Apply two clustering techniques — K-Means and Agglomerative Clustering — and evaluate the clusters they produce
- Visualize and analyze the clusters using a heatmap to reveal similarities within and across clusters

## 🔍 Key Insights
- **PCA Effectiveness**: PCA effectively captured most of the dataset's variance using the first few components, simplifying analysis without major information loss
- **Consistent Clustering**: K-Means and Agglomerative Clustering produced consistent cluster groupings that reflect regional crime rate similarities among states
- **Clear Distinctions**: The heatmap visualization highlighted strong intra-cluster similarities and clear distinctions between clusters

## 🛠️ Tools & Technologies
- **Python**
- **Jupyter Notebook**
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy

## 📁 Deliverables
- **Jupyter Notebook**: `unsupervised_task.ipynb`
- **Visualizations**: PCA biplot, correlation heatmap, and cluster plots
- **Interpretive analysis** summarizing PCA findings and cluster behaviors
