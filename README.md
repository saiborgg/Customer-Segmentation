# Customer-Segmentation
This project applies unsupervised machine learning to perform customer segmentation, a key task in marketing and customer relationship management. Using K-Means Clustering, the goal is to group customers based on purchasing behavior and demographic attributes without any prior labels.

The dataset includes features such as spending score, income, and age. These variables help uncover natural groupings of customers with similar characteristics. Since no target labels are provided, the algorithm discovers patterns purely based on data distribution.

K-Means clustering partitions data into k distinct clusters by minimizing the variance within each cluster. The optimal value of k is determined using the Elbow Method, which plots the within-cluster sum of squares (WCSS) against different values of k. The "elbow" point on the graph indicates a suitable number of clusters where adding more groups yields diminishing returns.

For visualization and exploratory analysis, Seaborn and Matplotlib are used to create intuitive plots that reveal the structure of the customer segments and validate the clustering results visually.

This project demonstrates how unsupervised learning, combined with data visualization techniques, can be used to extract actionable insights for targeted marketing and strategic business decisions.
