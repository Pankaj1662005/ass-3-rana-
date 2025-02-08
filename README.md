# Comparative Performance Study of Clustering Algorithms

## Overview
This project presents a comparative analysis of various clustering algorithms using different preprocessing techniques. The focus is on evaluating the performance of these algorithms using multiple evaluation metrics to determine the most effective clustering approach.

## Dataset
- **Name**: Iris Dataset  
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)  
- **Description**: The dataset consists of 150 samples from three species of Iris flowers (*Iris setosa*, *Iris versicolor*, and *Iris virginica*). Four features were measured from each sample: sepal length, sepal width, petal length, and petal width.

## Preprocessing Techniques
1. **Standardization**: Features are scaled to have zero mean and unit variance.
2. **Min-Max Normalization**: Features are scaled to a fixed range [0, 1].
3. **PCA (Principal Component Analysis)**: Dimensionality reduction to 2 principal components for visualization and analysis.

## Clustering Algorithms
1. **K-Means Clustering**
2. **Agglomerative Hierarchical Clustering**
3. **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**

## Evaluation Metrics
1. **Silhouette Score**: Measures the similarity of points within a cluster.
2. **Davies-Bouldin Index**: Evaluates intra-cluster similarity and inter-cluster differences.
3. **Adjusted Rand Index (ARI)**: Compares the clustering results with true labels (applicable to datasets with ground truth).

## Visualization
The following graph shows the Silhouette Scores for different algorithms and preprocessing techniques:

![download](https://github.com/user-attachments/assets/3281eebe-632d-4e06-9b4d-b9e2404af2e9)

## Conclusion
Based on the Silhouette Score, Davies-Bouldin Index, and Adjusted Rand Index, the most effective clustering method and preprocessing technique combination can be identified. The analysis demonstrates the impact of preprocessing on clustering performance and highlights the strengths and weaknesses of each algorithm.

## How to Run
1. Clone this repository:
    ```bash
    git clone https://github.com/Pankaj1662005/ass-3-rana-
    ```
2. Open the notebook in Google Colab:
    - Go to [Google Colab](https://colab.research.google.com/).
    - Click on **File > Open Notebook > GitHub**.
    - Enter the repository URL and open the notebook.
3. Run all cells to reproduce the results.

## License
This project is licensed under the MIT License.

## Contact
For any queries, feel free to contact **Pankaj** at [pankajsheokand2005@gmail.com].

