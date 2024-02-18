# Clustering Analysis using Pycaret

The following notebook utilizes Pycaret python package to accomplish a comparitive performance study of different clustering algorithms using a combination of pre-processing techniques and varying number of clusters on different evaluation parameters.

## Dataset description-

![Dataset](./public/dataset.PNG)

### Following Clustering models have been used-

1. K-means Clustering
2. Heirarchial Clustering
3. K-means Shift Clustering

### Following preprocessing techniques have been used in a variety of combinations-

1. Normalization
2. Transformation
3. Principle Component Analysis

### Following evaluation parameters have been considered-

1. Silhouette Score
2. Callinski-Harabasz
3. Davies-Bouldin

## Results-

![Table](./public/table.PNG)

## 1. For K-means Clustering, best performance was achieved without any preprocessing-

#### Cluster plot-

![cluster plot](./public/kmeans_cluster.PNG)

#### 3D plot-

![tsne plot](./public/kmeans_tsne.PNG)

#### Elbow plot-

![elbow plot](./public/kmeans_elbow.PNG)

## 2. For Heirarchial Clustering, best performance was achieved with Normalization-

#### Cluster plot-

![cluster plot](./public/heir_cluster.PNG)

#### 3D plot-

![tsne plot](./public/heir_tsne.PNG)

#### Elbow plot-

![elbow plot](./public/heir_elbow.PNG)

## 3. For K-means Shift Clustering, best performance was achieved with Normalization-

#### Cluster plot-

![cluster plot](./public/shift_cluster.PNG)

#### 3D plot-

![tsne plot](./public/shift_tsne.PNG)
