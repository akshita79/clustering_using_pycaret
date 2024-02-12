# Clustering Using Pycaret
Performing different clustering algorithms using pre-processing techniques with different number of clusters and then comapring the results.


# Dataset

The three clustering techniques I have used are:
1. K means Clustering
   ![k-means-clustering-algorithm-in-machine-learning](https://github.com/akshita79/clustering_using_pycaret/assets/92212914/916c44c3-a6dc-43c3-9331-46c2e55d6af3)

3. Hierarchical Clustering
   ![1*VvOVxdBb74IOxxF2RmthCQ](https://github.com/akshita79/clustering_using_pycaret/assets/92212914/11bd976a-029f-4663-9a45-132c50ffebc2)

4. DBSCAN
   ![fig-1-300x300](https://github.com/akshita79/clustering_using_pycaret/assets/92212914/753f2918-0255-418f-b22e-1a65cec93a23)


# Evaluation Parameters:
1. Silhouette
2. Calinski-Harabasz
3. Davies-Bouldin

# The Pre-Processing techniques:
1. Normalization
2. PCA (Principle Component Analysis)
3. Transform
4. Scale

The absence of a 'scale' column in the DBSCAN results is because DBSCAN does not utilize distance-based similarity metrics in the same manner as KMeans or hierarchical clustering algorithms, hence it is not as directly influenced by scaling.

The graphs of the different clustering algorithms are given below:
<img width="832" alt="Screenshot 2024-02-09 at 6 09 40 PM" src="https://github.com/gandhi25samar/Clustering-Assignment-102103145/assets/95834377/08cbdbe4-6669-4fd4-b8e8-e7f1f6dfd586">
<img width="842" alt="Screenshot 2024-02-09 at 6 09 32 PM" src="https://github.com/gandhi25samar/Clustering-Assignment-102103145/assets/95834377/05ad2829-6cc6-4b27-8b9a-fc5d896311fb">
<img width="845" alt="Screenshot 2024-02-09 at 6 09 24 PM" src="https://github.com/gandhi25samar/Clustering-Assignment-102103145/assets/95834377/ca2e27f0-23a2-40ad-b969-3e95fe4b7f3c">



