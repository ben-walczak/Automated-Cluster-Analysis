# Automated-Cluster-Analysis

Ben Walczak
Assignment 4
1.	The datasets I will be using are focused around red wine and white wine. The datasets were acquired using the help of UC Irvine Machine Learning Repository. Both red and white wines are types of Portuguese “Vinho Verde” wine.  Both datasets have the same attributes: fixed acidity, volatile acidity, citric acid, residual sugar, chloride, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol, and quality. These attributes are chemical components that make up the wine.

Using clustering, I hope to discover either subtypes of the red and white wines or a common factor for the quality of a wine.

2.	I scattered and clustered the data of red wine and white wine separately. The data was visualized in two dimensions. One dimension was quality. The other dimension varied depending on the columns being iterated through. Each graph was visualized with each color representing a different cluster. Each cluster also contained a centroid, which was visualized in gold. In addition to testing out all attributes against quality, I also tested how the number of clusters affected the output of the visualization. I used 2, 3, 4, and 5 clusters to visualize the data.

Although, I was hoping to discover how an attribute related to better-quality wine, I did discover that free sulfur dioxide and total sulfur dioxide affected the position of the centroid more than any other attribute. After this discovery, I decided to visualize free sulfur dioxide versus total sulfur dioxide using 2 and 5 clusters for both red and white wine. The clusters this time were clearly split. The ideal number of clusters I felt that represented the data the best for both red and white wines were 4 clusters. When visualizing 4 clusters of quality versus total sulfur dioxide, an ideal trend of sulfur dioxide appeared in one of the clusters to create a better-quality wine.
