# Machine Learning Project - Unsupervised Learning

## Project/Goals
The goal of this project was to perform unsupervised learning on a "Wholesale Data" dataset. This dataset refers to clients of a wholesale distributor and includes the annual spending in monetary units (m.u.) on diverse product categories. The following stages were performed on the data set provided:
- Exploratory data analysis
- Preprocessing
- KMeans Clustering
- Hierarchial Clustering
- PCA

## Process
### EDA & Preprocessing

- Generated summary statistics to look at distribution
- Looked for missing values and outliers
- Generated a Correlation matrix to see which variables had the strongest relationship
- Grouped by 'Channel' and calculated the sum for each category to see where there was the most spending
- Determined Feature Importance
#### Summary Statistics Outcome
<img src="images/Summary Statistics (Unsupervised Learning).png" alt="Notebook">

#### Boxplot For Outliers
<img src="images/Boxplot for Outliers.png" alt="Notebook">

#### Correlation Matrix
<img src="images/Correlation Matrix - Unsupervised Learning.png" alt="Notebook">

#### Sum for Each Category
<img src="images/Channel Group & Sum For Each Category.png" alt="Notebook">

#### Feature Importance
<img src="images/Feature Importance.png" alt="Notebook">



### KMeans Clustering
The objective of the analysis was to group similar products together into clusters based on their attributes. To perform the k-means clustering analysis, the following was done:
- Pre-processed the dataset
- Determined the optimal number of clusters
- Determined Cluster Centroids

#### Elbow Method fpr Optimal # of Clusters
<img src="images/Elbow Method.png" alt="Notebook">

#### Cluster Centroids
<img src="images/Cluster Centroids.png" alt="Notebook">

#### Pairplot For Cluster to Show Relationship
<img src="images/Pairplot For Clusters.png" alt="Notebook">


#### Hierarchial Clustering

Hierarchical clustering was used to identify patterns and group similar data points together in a hierarchy, resulting in a dendrogram

#### Dendrogram
<img src="images/Hierarchial Dendrogram.png" alt="Notebook">


### PCA
Principal component analysis (PCA) was performed to draw conclusions about the underlying structure of the wholesale customer data. Since using PCA on a dataset calculates the dimensions which best maximize variance, we will find which compound combinations of features best describe customers.

#### Feature Loadings determined to indicate the contribution of each original feature to each principal component.
<img src="images/Feature Loading.png" alt="Notebook">

#### Cumulative explained variance plot was used to help decide how many principal components to retain. Scatter plot was generated to visualize the first two principal components.
<img src="images/Cumulative Explained Variance & Scatter Plot.png" alt="Notebook">




## Project Outcomes
- The strongest correlation is between channel, milk, grocery and detergents_paper
- Channel 1 spent the most on fresh while Channel 2 spent the most on groceries
- Using the elbow method, the optimal k was determined to be 6 which makes sense given the amount of categories there were for spending
- Unsupervised Learning allowed the realization of spending trends to gain insights into what is being purchased the most and where. It makes it easier to predict knowing which items are more strongly related 
