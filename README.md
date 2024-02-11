# Machine Learning Project - Unsupervised Learning

## Project/Goals
The goal of this project was to perform unsupervised learning on a "Wholesale Data" dataset. This dataset refers to clients of a wholesale distributor and includes the annual spending in monetary units (m.u.) on diverse product categories. The following stages were performed on the data set provided:
- Exploratory data analysis
- Preprocessing
- Kmeans Clustering
- Hierarchial Clustering
- PCA

## Process
### EDA

- Generated summary statistics to look at distribution
- Looked for missing values and outliers
- Generated a Correlation matrix to see which variables had the strongest relationship
- Grouped by 'Channel' and calculated the sum for each category to see where there was the most spending
- Determined Feature Importance

<img src="images/Summary Statistics (Unsupervised Learning).png" alt="Notebook">
<img src="images/Boxplot for Outliers.png" alt="Notebook">
<img src="images/Correlation Matrix - Unsupervised Learning.png" alt="Notebook">
<img src="images/Channel Group & Sum For Each Category.png" alt="Notebook">





## Project Outcomes
- The strongest correlation is between channel, milk, grocery and detergents_paper
- Channel 1 spent the most on fresh while Channel 2 spent the most on groceries
- Using the elbow method, the optimal k was determined to be 6 which makes sense given the amount of categories there were for spending
- Unsupervised Learning allowed the realization of spending trends to gain insights into what is being purchased the most and where. It makes it easier to predict knowing which items are more strongly related 
