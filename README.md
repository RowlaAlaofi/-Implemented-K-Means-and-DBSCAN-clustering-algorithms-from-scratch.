# Machine Learning project

## 📚 **Project Overview**
This repository contains a machine learning project focused on traditional clustering techniques, specifically K-means and DBSCAN. The project includes the generation of synthetic datasets and a comparison of the clustering performance on various types of data.

## 🗂 **Project Structure**
The project is divided into two main parts:

1. **K-means Clustering**  
   - A popular clustering algorithm that partitions data into distinct groups based on similarity.  
   - Efficient for large datasets but requires specifying the number of clusters (K).  
   - Works well with spherical-shaped clusters.

2. **DBSCAN Clustering**  
   - A density-based clustering algorithm capable of detecting clusters of arbitrary shapes.  
   - Does not require specifying the number of clusters.  
   - Detects outliers by identifying points with low density.

## 📊 **Generated Datasets**
The project uses four different datasets created with scikit-learn functions:

1. **Blobs**: Gaussian-distributed clusters.  
2. **Anisotropic Blobs**: Linearly transformed blobs.  
3. **Moons**: Two interleaving half-circles.  
4. **Circles**: Concentric circles.

## 📈 **Results & Comparison**
Each dataset was analyzed using both K-means and DBSCAN, with comparisons based on:

- Visual representation of clusters.  
- Statistical measures including F1 Score, Normalized Mutual Information (NMI), and Rand Index.


