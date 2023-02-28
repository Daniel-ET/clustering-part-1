# Clustering-part-1

The aim of this notebook is to explore clustering.

### **The Dataset**

We will use the Iris flower dataset. The Iris flower fataset is a classic dataset used to identify types of flowers based on features describing their petals. We will load the dataset directly from the scikit-learn machine learning library.

After loading the dataset, we will extract two of the attributes and will run the K-means algorithm to obtain 3 clusters. We will only work with the first two attributes (sepal length, sepal width), which will be stored in the variable X.

![image](https://user-images.githubusercontent.com/96924468/221917354-92882bc2-7e36-4030-90e1-fddb48fe0aed.png)

### **K Means Initialisation**

K-means uses K centroids to represent each cluster and clusters are formed by assigning samples to the closest centroid. We will set K=3. Then, the samples in the dataset will be assigned to the nearest centroid, which will result in K=3 clusters

![image](https://user-images.githubusercontent.com/96924468/221918721-bdcd55ee-0dbc-4469-9bb4-078c0800f2ea.png)

As we can see, there are 3 centroids represented by a cross of a different colour. Samples are represented by a circle whose colour corresponds to the cluster they have been assigned to. The 3 resulting clusters consist of samples that are close to one another. However, samples in different clusters are also close to one another.

### ** K means iterative update**

K-means proceeds iteratively by

1. Updating the centroids as the centre of each cluster
2. Reassigning the samples to the new centroids
