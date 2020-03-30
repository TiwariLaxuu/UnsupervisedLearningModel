# UnsupervisedLearningModel
Here, these model represent Machine Learning unsupervised Clustering algorithm. 
Presented clustering algorithm are:-

K-Means Clustering:- It is iterative algorithm with non overlapping cluster where each data belongs to one cluster. Data in same cluster are very similar while different cluster have different. Similarity of cluster measure by using euclidean-based distance or correlation-based distance. It is very popular and used in various applications.

Hierarchical Clustering(HC):- It is same as K-Means Clustering but have different process. It start by treating each datapoint as seprate cluster. Then identify closest one and merge become one cluster, this step run until it become one cluster. The main output of Hierarchical clustering is dendrogram which shows hierarchical relationship between cluster. Two type of HC are: Agglomerative and Divisive.

Data of supermarket is provided to predict which type of person mainly visit supermarket based on salary and spending score.

1st we use K-Means algorithm to distinguish type of person [‘careless’, ‘Sensible’, ‘Careful’, ‘Target’, ‘Standard’]. Here, we use K-means++ to find number of cluster. From k-Means we conclude no. of cluster = 5. 

2nd we use HC agglomerative algorithm predicted same value as K-Means. From dendrogram we find optimal number of cluster. 

Both results are visualized using matplotlib.
