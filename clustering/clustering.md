# Clustering in Machine Learning

Clustering is an unsupervised machine learning technique used to group similar data points together based on their features. It helps discover inherent structures or patterns in datasets without predefined labels.

## Common Clustering Methods

- **K-Means**: Partitions data into _k_ clusters by minimizing within-cluster variance.
- **Hierarchical Clustering**: Builds nested clusters using either agglomerative (bottom-up) or divisive (top-down) approaches.
- **DBSCAN**: Groups points that are closely packed together, marking outliers as noise.
- **Gaussian Mixture Models (GMM)**: Assumes data is generated from a mixture of several Gaussian distributions.

## Pros

- Reveals hidden patterns and structures in data.
- No need for labeled data.
- Useful for exploratory data analysis and preprocessing.

## Cons

- Choosing the right number of clusters can be challenging.
- Sensitive to feature scaling and initialization.
- May struggle with clusters of varying shapes, sizes, or densities.
