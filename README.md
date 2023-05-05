# Crypto Clustering - Module 10 Application
## Project Overview
This project leverages Python's financial and unsupervised learning skills to cluster cryptocurrencies based on their price change data across different periods. The data is sourced from a provided CSV file.

Key aspects of this project include data importation, data preparation, determination of the optimal value for 'k', cryptocurrency clustering using K-means, cluster optimization with Principal Component Analysis (PCA), and visualization and comparison of the results.

## Steps
The project is divided into the following steps:

1. Import the Data
- The starter code provided includes the necessary instructions to import the data from the CSV file.

2. Prepare the Data
- The starter code also includes instructions on how to prepare the data for further analysis.

3. Find the Best Value for k Using the Original Data
- Determine the optimal number of clusters ('k') by using the Elbow Method on the original data.

4. Cluster Cryptocurrencies with K-means Using the Original Data
- Apply the K-means clustering algorithm on the original data, based on the optimal 'k' determined in the previous step.

5. Optimize Clusters with Principal Component Analysis (PCA)
- Use PCA to optimize the clusters by reducing the dimensionality of the original data, thereby capturing the most important aspects of the data.

6. Find the Best Value for k Using the PCA Data
- Reapply the Elbow Method, this time on the PCA-transformed data, to find the optimal 'k'.

7. Cluster the Cryptocurrencies with K-means Using the PCA Data
- Use K-means clustering algorithm on the PCA-transformed data, based on the new optimal 'k' value.

8. Visualize and Compare the Results
- Visualize the results of the clustering from the original data and the PCA-transformed data. Compare the results to assess the performance and efficiency of the PCA optimization.

## Tools and Libraries
This project utilizes Python programming language along with libraries such as pandas for data manipulation, scikit-learn for implementing machine learning algorithms like K-means and PCA, and matplotlib for data visualization.

## Conclusion
By the end of this project, you would have gained hands-on experience in clustering cryptocurrencies, determining the optimal number of clusters using the Elbow Method, applying PCA for dimensionality reduction, and visualizing and comparing clustering results.