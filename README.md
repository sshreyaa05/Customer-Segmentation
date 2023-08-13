# Customer-Segmentation
## PROBLEM STATEMENT:
The objective of this project is to segment the  customers in the dataset into distinct groups or clusters based on their similar behaviour. This segmentation process aims to uncover meaningful patterns and insights within the customer data, that aids in targeted marketing thereby, improves the business strategies.
## WHY WE ARE TRYING TO SOLVE THIS PROBLEM?
There reasons are as followed:
## 1. Continuous improvement - Machine learning models can be trained on historical data as well as the new updated data when it is available, leading to continuous improvement in the segmentation process
## 2. Exploration of hidden insights - It uncovers patterns and the hidden insights which was previously unknown, thereby, improving the business growth.
## 3. Unbiased decision making - Rather than subjective judgements, it helps in the unbiased decision making, hence, coming up with more data driven strategies for customer segmentation.
## How we are approaching this problem for solving it through k means clustering, Agglomerative and Density Based Spatial Clustering On Applications With Noise.
## 1. Visualizing the relationship between the Annual Income and Spending Score Using Scatterplot.
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/ce2dc987-ccae-423a-8ce4-7ce68394a233)
## 2. Clustering between the annual income and spending score using K-means algorithm, viewing the elbow method to determine the optimal value of K
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/2c40f9a0-deab-4589-b7fb-465012849a30)
## here, the number of clusters is 5
## 3. Visualising the clusters between annual income and spending score using K-Means clustering.
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/9b5a9115-7502-4de7-b398-bbafcd5eb0eb)
## 4. Visualising the silhoutte score using the silhoutte visualiser
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/16648cc3-6de1-4285-8af0-0072fca64d1f)
## the silhoutte score is 0.554
## 5. Clustering between age and spending score using K-Means algorithm, viewing the elbow method to find the value of K
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/bc0776f1-43c7-4ac6-9878-08a40d6a9cbb)
## here, the optimal value of K is 4
## 6. Visualising the clustering
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/ea676891-6efe-4fa5-a493-e921474aee75)
## 7. Visualising the silhoutte visualiser
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/7a4f3f34-ac95-4da8-8aa3-1b1afd05ba80)
## The silhoutte score is 0.500
## 8. Clustering the Multiple dimensions, determining the optimal value of K using elbow method
## ![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/f5d0b6c3-0f47-45dd-b0ec-260b6ae816d6)
## the optimal value of K is 6
## We got the 6 clusters labelled as  1,2,3,4,5 and 6.
## NOW LETS CLUSTER THE CUSTOMERS USING AGGLOMERATIVE AND DBSCAN CLUSTERING 
## Dendrogram formation for hierarchical clustering
## ![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/3de6d389-cdff-4e1b-9d81-5177d3351036)
## We draw a horizontal line through the linkages that are the longest. The cluster that cuts the maximum number of lines is the optimally chosen number of clusters.Whenever the data is in spherical shape, K-means algorithm is used. Whereas hierarchical clustering is used for social networking methods
## Clustering with Agglomerative Clustering 
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/878edd41-e0ad-448b-9fa1-fb34f98d1486)
## here the number of clusters are 5
## Now, K-Means vs Hierarchical 
As we know, clustering is a subjective statistical analysis, and there is more than one appropriate algorithm for every dataset and type of problem. So how to choose between K-means and hierarchical?
- 1. If there is a specific number of clusters in the dataset, but the group they belong to is unknown, choose K-means
- 2. If the distinguishes are based on prior beliefs, hierarchical clustering should be used to know the number of clusters
- 3. With a large number of variables, K-means compute faster 
- 4. The result of K-means is unstructured, but that of hierarchal is more interpretable and informative
- 5. It is easier to determine the number of clusters by hierarchical clustering’s dendrogram
## Now, Lets begin with the DBSCAN Clustering
## ### To calculate EPS point parameter, we will calculate the distance from each point to its closest neighbours 
### using the nearest neighbours
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/6168963a-acd0-454f-8fe1-545815289ce9)
## Visualising the DBSCAN clustering for income and spending score
![image](https://github.com/sshreyaa05/Customer-Segmentation/assets/132264752/b86b80ba-8f33-40df-be99-9d55bcc49bfa)
## lastly we fetch the silhoutte score of 0.388.










