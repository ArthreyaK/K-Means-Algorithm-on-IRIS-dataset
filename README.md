# Iris Flower Clustering with K-Means

![Iris Flowers](https://github.com/ArthreyaK/K-Means-Algorithm-on-IRIS-dataset/blob/main/iris%20flower.png)

## Overview

This project applies the K-Means clustering algorithm to the Iris dataset for clustering Iris flowers based on their sepal and petal areas. The sepal and petal areas are computed by multiplying the sepal length and width, and the petal length and width respectively. K-Means clustering is then used to group the flowers into three clusters based on these derived features.

## Dataset

The Iris dataset consists of 150 samples of Iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The dataset is commonly used for classification and clustering tasks in machine learning.

## Methodology

- **Feature Engineering:** The sepal and petal areas are computed by multiplying the respective length and width features.
- **K-Means Clustering:** The K-Means algorithm is applied to the feature-engineered data to group the flowers into three clusters based on their sepal and petal areas.

## Visualization

![Clustered Iris Flowers](clustered_iris_flowers.jpg)

The scatter plot above shows the Iris flowers clustered into three groups based on their sepal and petal areas. Each cluster is represented by a different color, and the centroids of the clusters are marked with black circles.

## Evaluation

To evaluate the performance of the K-Means clustering algorithm, a confusion matrix is computed by comparing the predicted clusters with the actual class labels of the Iris flowers. This provides insight into how well the clusters align with the true classes in the dataset.

## Future Work

- **Hyperparameter Tuning:** Experiment with different values of K (number of clusters) to optimize the clustering performance.
- **Visualization Enhancements:** Explore other visualization techniques to better understand the clusters and their characteristics.
- **Feature Selection:** Investigate the impact of including or excluding certain features on the clustering results.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

