# Comparison and Evaluation of 8 Clustering Algorithms (implemented both from-scratch and using scikit-learn) on Toy Dataset & VOC-bboxes Dataset:

This project was our final project for the course. 

As a group project, performing 8 clustering algorithms on 2 datasets, each originated from different distributions and data shapes, wouldn't have been accomplished without the efforts of my clever and creative colleagues; Narjes Noorzad and Hamidreza Ali Akbari Khoyi. 


Algorithms implemented in this project include:

1. K-means Clustering 
2. Agglomerative Clustering
3. DBSCAN Clustering 
4. Spectral Clustering 
5. GMM Clustering 
6. Affinity Propagation 
7. OPTICS‌ Clustering 
8. Meanshift Clustering 

The algorithms are implemented both using scikit-learn and from scratch. (Except for OPTICS, Meanshift and K-means)
(K-means algorithm is implemented from scratch in HW#4, which is also uploaded in this repository.)



For evaluation and comparison among these algorithms in our case study, we used several metrics including:

1. Silhouette Score for all scikit-learn implementaions 
2. Separation Index, Fisher Discrimination Index on a barchart visualization for all from-scratch implementations 
3. BIC/AIC score for GMM with sci-kit learn
4. Reachability plot for OPTICS



Parameter Tuning was a very important part of this project. Tuning is basically the tool which can be used besides evaluation to leverage an algorithm's performance. 

Comparisons can be drawn between the from-scratch group of algortihms and the scikit-learn ones as well by plotting a common evaluation metric for them on a barchart.

More details are accessible in both Clustering Report and Clustering Slides pdf files located in the "Documents" directory
