# Clustering Using Pycaret
Performing different clustering algorithms using pre-processing techniques with different number of clusters and then comapring the results.


# Dataset

The three clustering techniques I have used are:
1. K means Clustering
3. Hierarchical Clustering
4. DBSCAN

# Evaluation Parameters:
1. Silhouette
2. Calinski-Harabasz
3. Davies-Bouldin

# The Pre-Processing techniques:
1. Normalization
2. PCA (Principle Component Analysis)
3. Transform
4. Scale

# Results
The absence of a 'scale' column in the DBSCAN results is because DBSCAN does not utilize distance-based similarity metrics in the same manner as KMeans or hierarchical clustering algorithms. Hence it is less directly influenced by scaling.
The results of the above algorithms are saves as separate csv files.

Graphs :
<img width="832" alt="Screenshot 2024-02-09 at 6 09 40 PM" src="https://github.com/gandhi25samar/Clustering-Assignment-102103145/assets/95834377/08cbdbe4-6669-4fd4-b8e8-e7f1f6dfd586">
<img width="842" alt="Screenshot 2024-02-09 at 6 09 32 PM" src="https://github.com/gandhi25samar/Clustering-Assignment-102103145/assets/95834377/05ad2829-6cc6-4b27-8b9a-fc5d896311fb">
<img width="845" alt="Screenshot 2024-02-09 at 6 09 24 PM" src="https://github.com/gandhi25samar/Clustering-Assignment-102103145/assets/95834377/ca2e27f0-23a2-40ad-b969-3e95fe4b7f3c">



