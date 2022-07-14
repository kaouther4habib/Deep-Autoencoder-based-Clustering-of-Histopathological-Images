# Deep-Autoencoder-based-Clustering-of-Histopathological-Images

## Table of contents
* [Proposed Method](#proposed-method)
* [Technologies](#technologies)


## Proposed Method:
Our study has been performed on Histopathology Images ”Mitos-atypia” provided from ”Grand Challenge”[Capron, 2014] The following steps are included in the process:
First , we began developing our model by importing our data set.Then We pre-processed the images for the second stage. To accomplish this, we resized the images to (96x96), which is appropriate for the architecture we used. and convert to black and white using COLOR_BGR2GRAY.The data was then divided into two groups: training and testing.And we did experiments with three different types of autoencoders, each with all five clustering algorithms (kmeans-hdbscan -dbscan-hierarchical-meanshift) and finally we applied evaluation metrics (Silhouette, Davies Bouldin)
to the obtained results as figure demonstrates:
![alt text](https://github.com/kaouther4habib/Deep-Autoencoder-based-Clustering-of-Histopathological-Images/blob/master/images/architecture.png)

## Technologies
Project is created with:
* TensorFlow
* Sklearn
* Keras
