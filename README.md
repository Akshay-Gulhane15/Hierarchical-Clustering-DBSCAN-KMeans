# Hierarchical-Clustering-DBSCAN-KMeans

1.HIERARCHICAL CLUSTERING:




-Hierarchical clustering is a method of cluster analysis that builds a hierarchy of clusters.

-It starts with each data point as its own cluster and then iteratively merges or splits clusters based on a specified criterion, such as distance or similarity.

-There are two main types of hierarchical clustering: agglomerative (bottom-up) and divisive (top-down).

-Agglomerative hierarchical clustering starts with each point as a separate cluster and then merges the closest clusters until only one cluster remains.

-Divisive hierarchical clustering starts with all points in one cluster and then recursively splits the cluster into smaller clusters until each point is in its own cluster.

-Hierarchical clustering does not require specifying the number of clusters beforehand and can be visualized using dendrograms.







2.DBSCAN (Density-Based Spatial Clustering of Applications with Noise):

-DBSCAN is a density-based clustering algorithm that groups together points that are closely packed together based on a density criterion.

-It works by defining clusters as continuous regions of high density separated by regions of low density.

-DBSCAN requires two parameters: epsilon (eps), which defines the radius within which to search for neighboring points, and minPoints, which specifies the minimum number of points required to form a dense region (core point).

-Points that are within the epsilon distance of a core point are considered part of the same cluster, while points that are not within the epsilon distance of any core point are considered noise or outliers.


3.K-MEANS CLUSTERING:




-K-means clustering is a centroid-based clustering algorithm that partitions data into a specified number of clusters (k).

-It works by iteratively assigning each data point to the nearest centroid and then recalculating the centroids based on the mean of the points assigned to each cluster.

-The algorithm converges when the centroids no longer change significantly or after a specified number of iterations.

-The number of clusters (k) is a hyperparameter that needs to be specified before running the algorithm.

-K-means clustering is sensitive to the initial placement of centroids and may converge to a local minimum, so multiple initializations with different starting centroids are often used to improve robustness.
