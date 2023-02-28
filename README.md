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

Until the stop criterion it met.

![image](https://user-images.githubusercontent.com/96924468/221921256-89e3ad7e-2227-4345-9614-78b0d90087af.png)
![image](https://user-images.githubusercontent.com/96924468/221921337-cc3ab35f-b145-436b-b193-4ad1d8b737de.png)
![image](https://user-images.githubusercontent.com/96924468/221921415-a9931d4b-b6f1-4e55-8378-c52ea3fca56c.png)
![image](https://user-images.githubusercontent.com/96924468/221921497-89dfb686-4cee-4831-a41a-b43835795595.png)
![image](https://user-images.githubusercontent.com/96924468/221921573-2ea22977-f1fd-4c73-a6d8-30f8b838e082.png)
![image](https://user-images.githubusercontent.com/96924468/221921691-ab9b44e8-2f53-4b1f-a979-807d76e31fe1.png)
![image](https://user-images.githubusercontent.com/96924468/221921773-698c5aa5-9849-49d2-82c8-d6e212e47f24.png)
![image](https://user-images.githubusercontent.com/96924468/221921869-a41e3f1b-d03a-440c-9506-d5770382d5e2.png)
![image](https://user-images.githubusercontent.com/96924468/221921971-85af0646-ef23-4eeb-b8f4-f5cd204b1993.png)
![image](https://user-images.githubusercontent.com/96924468/221922050-803bf5c3-d456-446e-b75a-c7194cd8a7fd.png)
![image](https://user-images.githubusercontent.com/96924468/221922125-e4ca08cc-7505-4a5c-8d98-be4441481ae6.png)
![image](https://user-images.githubusercontent.com/96924468/221922180-be08938d-b3b3-4648-9bae-2cc803fb1e02.png)
![image](https://user-images.githubusercontent.com/96924468/221922252-e355d305-7694-4632-95fe-6bf0ac387841.png)
![image](https://user-images.githubusercontent.com/96924468/221922326-56fb504b-aacf-46a1-8761-434e2cd94999.png)
![image](https://user-images.githubusercontent.com/96924468/221922393-e2212bc4-4d35-4aab-8991-374b6b21f714.png)






















