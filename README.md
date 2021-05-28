# K-means-Clustering
Unsupervised - K-means clustering

K-means clustering is one of the simplest and popular unsupervised ML algorithms. The objective of K-means is to group/cluster similar data points together and discover underlying patterns. To achieve this objective, K-means looks for a fixed number (k) of clusters in a dataset.
A cluster refers to a collection of data points aggregated together because of certain similarities.
You will define a target number k, which refers to the number of centroids you need in the dataset. A centroid is the imaginary or real location representing the center of the cluster.
Every data point is allocated to a cluster through reducing the in-cluster sum of squares.
In other words, the K-means algorithm identifies k number of centroids, and then allocates every data point to the nearest cluster, while keeping the centroids as small as possible.
The “means” in the K-means refers to averaging of the data to find the centroid.

For this project we will attempt to use KMeans Clustering to cluster Universities into to two groups, Private and Public.

It is very important to note, we actually have the labels for this data set, but we will NOT use them for the KMeans clustering algorithm, since that is an unsupervised learning algorithm.

When using the Kmeans algorithm under normal circumstances, it is because you don't have labels. In this case we will use the labels to try to get an idea of how well the algorithm performed, but you won't usually do this for Kmeans, so the classification report and confusion matrix at the end of this project, don't truly make sense in a real world setting!.

The Data
We will use a data frame with 777 observations on the following 18 variables.

1	Private A factor with levels No and Yes indicating private or public university
2	Apps Number of applications received
3	Accept Number of applications accepted
4	Enroll Number of new students enrolled
5	Top10perc Pct. new students from top 10% of H.S. class
6	Top25perc Pct. new students from top 25% of H.S. class
7	F.Undergrad Number of fulltime undergraduates
8	P.Undergrad Number of parttime undergraduates
9	Outstate Out-of-state tuition
10	Room.Board Room and board costs
11	Books Estimated book costs
12	Personal Estimated personal spending
13	PhD Pct. of faculty with Ph.D.’s
14	Terminal Pct. of faculty with terminal degree
15	S.F.Ratio Student/faculty ratio
16	perc.alumni Pct. alumni who donate
17	Expend Instructional expenditure per student
18	Grad.Rate Graduation rate


