# Credit Card Data Clustering - Unsupervised Machine Learning Project

This project explores clustering techniques on credit card customer data using various unsupervised machine learning algorithms. The aim is to group customers into clusters based on their usage patterns, providing insights for targeted marketing strategies and business decisions.

## Dataset

- **Dataset**: `CC GENERAL.csv`
- **Description**: This dataset contains anonymized credit card customer data, with features representing customer behavior such as balance, purchases, payments, and credit limits.

## Clustering Algorithms Used

1. **K-Means Clustering**
   - A partition-based clustering technique that divides data into `k` clusters by minimizing the distance between data points and their assigned cluster centers.

2. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
   - A density-based algorithm that clusters data points that are close to each other and marks points in low-density areas as outliers.

3. **GMM (Gaussian Mixture Model)**
   - A probabilistic clustering method that models data as a mixture of Gaussian distributions.

4. **Heuristic Clustering**
   - A custom, rule-based clustering approach used to group similar customers based on certain predefined characteristics.

## Dimensionality Reduction Techniques

- **PCA (Principal Component Analysis)**: Used to reduce the dimensionality of the dataset and improve clustering performance.
- **t-SNE (t-Distributed Stochastic Neighbor Embedding)**: A non-linear dimensionality reduction method used for 2D visualization of high-dimensional data.

## Visualizations

- **Elbow Method**: Helps determine the optimal number of clusters for K-Means by plotting the sum of squared distances from each point to its assigned cluster center.
- **Silhouette Score**: Assesses the quality of the clustering by measuring how close each point is to its assigned cluster compared to other clusters.
- **t-SNE Plots**: Used to visualize the clusters formed by the different algorithms in a 2D space.

## Results

- **K-Means**: Generated distinct clusters but required careful selection of the number of clusters.
- **DBSCAN**: Successfully identified outliers but struggled with clusters of varying densities.
- **GMM**: Provided a soft clustering approach with probabilistic membership, helpful for uncertain or overlapping data points.
- **PCA** and **t-SNE**: Both techniques helped visualize the high-dimensional data in 2D, revealing clear clusters.

## Conclusion

Clustering credit card customer data provides valuable insights into customer segmentation. Each clustering technique offers a different perspective, with K-Means and GMM performing well in separating distinct groups, while DBSCAN effectively identifies outliers.
