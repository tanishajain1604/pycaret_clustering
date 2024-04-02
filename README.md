# Cluster Analysis with PyCaret

This Python script performs cluster analysis using different clustering techniques including K-Means clustering, Spectral Clustering, and Density-Based Spatial Clustering. It utilizes the PyCaret library for clustering and visualization.

## Setup

### Requirements
* Python 3.2.0
* PyCaret library

Install the required libraries using pip:

```
pip install pycaret
```

## Usage

1. Clone the repository or download the script.
2. Run the script in a Python environment.
3. Follow the prompts and instructions provided in the script.

## Script Overview

The script performs the following tasks:

1. Installation of PyCaret library.
2. Importing necessary libraries and dataset (Iris dataset in this case).
3. Setting up parameters for the clustering models.
4. Performing cluster analysis using different clustering techniques.
5. Visualizing the clustering results using various plots including 2D plot, 3D plot, elbow plot, silhouette plot, and distribution plot.

## Assignment Overview

The following tasks are performed in the assignment:

1. The clustering is performed for different algorithms in the notebook.
2. After this, tables are formed for each algorithm based on scores of different numbers of clusters (c=3, 4, 5) on different parameters (normalization, transformation, etc.) (attached CSV files).
3. The best clustering algorithm and the best number of clusters are found using the TOPSIS algorithm.
4. **The best clustering algorithm is Spectral Clustering and the best number of clusters is 3.**

   The plots, graphs, etc., are present in the notebook for better visualization.

## Additional Notes

* The dataset used in this script is the Iris dataset, which is commonly used for demonstration purposes.
* Different preprocessing techniques such as normalization, transformation, and PCA are also applied to the data before clustering.
* Ensure that you have sufficient computational resources as some operations, especially visualization of high-dimensional data, may require significant computational power.

