# Bank Marketing Project
### Data Set Information
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. More than one contact to the same client was required to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. Refers to the notebook for more details.
The Goal for 1st Notebook: Data Exploratory and Cleaning
An exploratory analysis is carried out to understand the data and to obtain some insights that would help me to make the further decision on how to preprocess the data.

### The Goal for 1st Notebook: Data Exploratory and Cleaning
An exploratory analysis is carried out to understand the data and to obtain some insights that would help me to make further decision on how to preprocess the data.

#### Methodology
1.	Explore the numeric attributes with visualizations and quantitative tables
2.	Explore the categorical attributes with visualizations and quantitative tables
3.	Remove outliers for numerical attributes
4.	Replace the "unknown" category placeholder with the mode value
5.	Data transformation
6.	Split the data into 80%,20% for future model building work

### The Goal for 2nd Notebook: Customer Segmentation Analysis
In this section, the unsupervised clustering technique is applied to learn the characteristic of different customer segments. I also analyze the shared features among clusters that are influential for clients to make their decision to subscribe the product.

#### Methodology
1.	Feature Selection: remove the less predictive features
2.	K means Clustering: Find optimal cluster number by elbow method and Silhouette score method
3.	Visualization: visualize the clustering results in 2D by applying the Principle Component Analysis to reduce the dimension
4.	Conduct the Customer Segmentation Analysis

4(a). look into the y variable distribution and evaluate the yes ratio of the clients who subscribe the product to the total number of clients in each cluster.

4(b). Evaluate the cluster centroids for the chosen clusters because cluster centroid is the mean of the cluster

4(c). Lastly, Look into the top 10 features from those clusters that influence the clients to subscribe the product most significantly by feature selection for further analysis.



