# Country-Based Clustering and Dimensionality Reduction

## Project Overview
This project focuses on **dimensionality reduction** and **clustering algorithms** using real-world socio-economic data.  
The dataset used is **[Unsupervised Learning on Country Data](https://www.kaggle.com/datasets)**, available publicly on Kaggle.  

Through this project, we aim to uncover hidden patterns among countries based on their socio-economic indicators using advanced unsupervised learning methods.

---

## Learning Objectives
By completing this project, you will be able to:

- Apply dimensionality reduction techniques such as:
  - **Principal Component Analysis (PCA)**
  - **t-Distributed Stochastic Neighbour Embedding (t-SNE)**
  - **Uniform Manifold Approximation and Projection (UMAP)**
- Implement and compare clustering algorithms:
  - **K-Means**
  - **DBSCAN**
- Visualize and interpret patterns in multi-dimensional data.
- Compare algorithm performance and discuss trade-offs.
- Relate the clustering results to real-world socio-economic insights.

---

## Project Structure

COUNTRY BASED PROJECT
│
├── artifacts/
│ └── figures/
│ ├── pca_cov_scatter.png
│ ├── PCA_Dbscan.png
│ ├── UMAP_Kmean.png
│ ├── tsne70_clusters.png
│ └── ... (visualizations)
│
├── clustering Algorithms/
│ ├── db_scan.ipynb
│ └── K_means_clustering.ipynb
│
├── data/
│ ├── processed/
│ └── raw/
│
├── data Preparation/
│ └── data_preparation.ipynb
│
├── dimensionality Reduction/
│ ├── pca.ipynb
│ ├── tsne.ipynb
│ └── umap.ipynb
│
├── requirements.txt
└── README.md

## Project Initialization

### Create a virtual environment

python -m venv venv
source venv/bin/activate  

### Install Dependencies

pip install -r requirements.txt



