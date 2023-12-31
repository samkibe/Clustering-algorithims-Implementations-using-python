### Clustering 
- refers to the mathematical and algorithmic process of grouping ‘n’ elements into ‘k’ distinct groups such that the groups so produced have more similarity among its members than among members belonging to different, distinct groups.
- - Affinity Propagation, Agglomerative Hierarchical clustering, 
- Expectation-Maximization Clustering using GMM, 
- DBSCAN clustering Algorithm, 
- Mean-shift algorithm, 
- K-Means algorithm, 
- OPTICS, 
- Gaussian Mixture Model, and BIRCH.
  

TASK: Implementation of clustering Algorithmns, by type.

1. Centroid-based Clustering
- We will do simple implementations of these algorithmns, they include, k-means, k_means++, k-medoids, k-modes et cetera
librarieskModes, kMeans
2. Density-based Clustering
- We will do simple implementations of these algorithmns, they include DBSCAN (Density-Based Spatial Clustering of Applications with Noise), OPTICS (Ordering Points To Identify the Clustering Structure), HDBSCAN (Hierarchical Density-Based Spatial Clustering of Applications with Noise), Mean Shift, Affinity Propagation et cetera.
make_classification generates datasets with numerical features, which may not be optimal for Density-based Clustering therefore we will utilize the make_blobs function to create a dataset with well-defined clusters: libraries: DBSCAN, MeanShift, AffinityPropagation.
3. Distribution-based Clustering
- We will do simple implementations of these algorithmns, they include Gaussian Mixture Model and Expectation-Maximization (EM) Clustering for these implementations we will still use the make_blobs function to create a dataset, libraries: GaussianMixture
- Expectation-Maximization (EM) is often used in conjunction with Gaussian Mixture Models (GMM), as the EM algorithm is employed to estimate the parameters of the GMM
4. Hierarchical Clustering
- We will do simple implementations of these algorithmns, they include Ward’s Method (Agglomerative Hierarchical Clustering), Hierarchical Clustering, Birch (Balanced Iterative Reducing and Clustering using Hierarchies) et cetera for these implementations we will still use the make_blobs function to create a dataset libraries: AgglomerativeClustering, Birch, SpectralClustering
### Finally, we compare the performances of some of these clustering algorithms, by considering metrics such as silhouette score, Davies-Bouldin index, and computational efficiency.

