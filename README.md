
# Machine Learning Project: Clustering and Dimensionality Reduction Analysis


This project explores unsupervised learning techniques, focusing on clustering analysis enhanced by dimensionality reduction for improved visualization and interpretability. We examine the performance of clustering algorithms on multiple datasets, with the application of Principal Component Analysis (PCA), Linear Discriminant Analysis (LDA), and Independent Component Analysis (ICA) to observe the effects on clustering results.


## Project Goals

* Evaluate Clustering Performance: Assess the clustering performance across datasets using various metrics.
* Dimensionality Reduction: Apply PCA, LDA, and ICA for visualization and performance impact.
* Visualization: Present the clustering and dimensionality reduction results to better interpret high-dimensional data.
## Datasets

The following datasets are used for clustering analysis:

* Iris Dataset (iris_results_df)
* Wine Dataset (wine_results_df)
* Breast Cancer Dataset (results_df_bc)
* Synthetic Blob Dataset (results_df_blob)
* Synthetic Moon Dataset (results_df_moon)
* Synthetic Concentric Dataset (results_df_c)
Each dataset’s results are stored in variables named according to the dataset.
## Algorithms and Techniques

### Clustering Algorithms

* KMeans: Applied to cluster the datasets, with results evaluated using clustering metrics.
### Dimensionality Reduction Techniques

* Principal Component Analysis (PCA): Used for visualizing data in 2D space by reducing features while retaining as much variance as possible.
* Linear Discriminant Analysis (LDA): Applied to maximize class separability, enhancing the clustering structure in lower dimensions.
* Independent Component Analysis (ICA): Used to identify and separate independent components within the data, offering insights into feature dependencies.
## Performance Matircs

To evaluate clustering quality, the following metrics are used:

* Silhouette Score
* Adjusted Rand Index (ARI)
* Calinski-Harabasz Index
* Davies-Bouldin Index
* Inertia (Within-cluster Sum of Squares)
* F1 Score
* Purity
* Homogeneity Score
* Completeness Score
* V-measure Score
## Project Structure

```bash
├── data/                         # Datasets used for clustering analysis
├── notebooks/                    # Colab notebooks for code and analysis
├── scripts/                      # Python scripts for clustering and dimensionality reduction
├── results/                      # Results and visualization files
├── README.md                     # Project documentation
└── analysis_report.md            # Detailed analysis report
```
## Results

Below are the results of the clustering and dimensionality reduction analysis across different datasets. Each section includes key performance metrics and visualizations for the Original, PCA, LDA, and ICA transformations.

### 1. Iris Dataset
#### Cluster Visualization
Original and PCA data clustering:
![Iris Original and PCA Clustering](https://github.com/AllenJose2110/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/Cancer%20-%20(LDA%20%26%20ICA).png)

LDA and ICA transformed data:
![Iris LDA and ICA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/Iris%20-%20(LDA%20%26%20ICA).png)

### 2. Wine Dataset
#### Cluster Visualization
Original and PCA data clustering:
![Wine Original and PCA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/Wine%20-%20(Original%20%26%20PCA).png)

LDA and ICA transformed data:
![Wine LDA and ICA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/Wine%20-%20(LDA%20%26%20ICA).png)

### 3. Breast Cancer Dataset
#### Cluster Visualization
Original and PCA data clustering:
![Breast Cancer Original Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/Cancer%20-%20(Original%20%26%20PCA).png)

LDA and ICA transformed data:
![Breast Cancer LDA and ICA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/Cancer%20-%20(LDA%20%26%20ICA).png)

### 4. Synthetic Dataset (make_blobs)
#### Cluster Visualization
Original and PCA data clustering:
![Synthetic Original and PCA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/blobs%20-%20(Original%20-%20PCA).png)

LDA and ICA transformed data:
![Synthetic LDA and ICA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/blobs%20-%20(LDA%20%26%20ICA).png)

### 5. Synthetic Dataset (make_moons)
#### Cluster Visualization
Original and PCA data clustering:
![Synthetic Original and PCA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/moons%20-%20(Original%20%26%20PCA).png)

LDA and ICA transformed data:
![Synthetic LDA and ICA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/moons%20-%20(LDA%20%26%20ICA).png)

### 6. Synthetic Dataset (make_circles)
#### Cluster Visualization
Original and PCA data clustering:
![Synthetic Original and PCA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/circles%20-%20(Original%20%26%20PCA).png)

LDA and ICA transformed data:
![Synthetic LDA and ICA Clustering](https://github.com/allenjose24/Dimentionality-Reduction-Using-PCA-LDA-and-ICA/blob/main/circles%20-%20(LDA%20%26%20ICA).png)

## Running the Project

### Clustering and Evaluation:

* Run the scripts or notebooks in notebooks/ to apply KMeans clustering and evaluate the performance across datasets.
### Dimensionality Reduction:

* Dimensionality reduction results can be visualized for each dataset in the provided notebooks.
### Visualization:

* Visualization of clustering results and dimensionality reduction can be found in the results/ directory or generated within notebooks.
## Future Enhancements

* Integration of Other Clustering Algorithms: Implement other clustering algorithms (e.g., DBSCAN, Hierarchical Clustering) to compare results.
* Additional Dimensionality Reduction Techniques: Explore t-SNE and UMAP for further insights.
* Hyperparameter Tuning: Refine clustering model parameters to optimize performance.
## Author

#### Allen Jose
Lead developer and researcher, working on clustering and dimensionality reduction techniques for high-dimensional data analysis.
