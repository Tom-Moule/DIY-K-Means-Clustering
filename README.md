# DIY-K-Means-Clustering
Building a K Means Clustering model from scratch, using python

K Means Clustering is an established unsupervised method for clustering data points into groups, in order to establish patterns. 

In this exercise, I wanted to apply my python skills and my understanding of the logic behind K means clustering to develop a clustering model from scratch. 

In order to evaluate the performance of my model, I benchmark my model’s performance against that of sklearn’s k means clustering model. In particular, I wanted to see whether I could achieve similar values for centroids and mean squared error for a given value of K.



## Description
My motivation for this project stems from a broader interest in the mathematics and logic that underpins machine learning. 

I was also motivated by the challenge of applying function-oriented reasoning to develop a clustering model that was built upon well defined functions that could be iteratively deployed to achieve the final outcome.

As part of this project, I first focused on the iris dataset, as I was interested to see if clustering algorithms could pick up the natural categorisations of iris species - and if alternative clusters were picked up that might represent finer grained subdivisions.

Having used SKlearn to explore the impact of varying K, and to find the centroids and MSE for K = 3 (the number of iris species), I then developed a DIY clustering model, which was able to achieve almost identical results for MSE and centroid positions. 

I then wanted to try my model on another dataset (with appropriate benchmarking against SKlearn). I did so on a breast cancer dataset, with similarly positive results.

## File Structure

- DIY_K_means_clustering.ipynb (The primary file for the project)
- Iris.csv
- breast-cancer.csv

