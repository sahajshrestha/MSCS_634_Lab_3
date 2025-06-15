# Clustering Wine Dataset - Lab 3

## Overview
This lab explores K-Means and K-Medoids clustering algorithms using the Wine dataset. Clustering performance is evaluated using the Silhouette Score and Adjusted Rand Index (ARI).

## Key Results
- K-Means achieved a Silhouette Score of `0.2848589191898987` and ARI of `0.8974949815093207`.
- K-Medoids achieved a Silhouette Score of `0.26597740204536796` and ARI of `0.7263406645756675`.
- K-Means appeared to produce better-defined clusters since it showed higher Silhouette Score as compared to K-Medoids. .

## Challenges
- Ran into python environment issue while installing `scikit-learn-extra` was required for K-Medoid and had to invest in a lot of time debugging and ended up using pyclustering instead. 

## Conclusion
K-Means generally performed better on this wine dataset.