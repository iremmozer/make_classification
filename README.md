# make_classification
# Hierarchical Clustering Behavior Analysis

My goal in this project is to model the different behaviors of hierarchical clustering variants on datasets.

First, I generated a plot using `make_classification` data based on the nearest-neighbor distance (single linkage), followed by a plot based on the farthest-neighbor distance (complete linkage). As is evident from the two plots, the graph generated using the farthest-neighbor method yields more distinct and interpretable results. 

Additionally, by using `fcluster` with a specified threshold value, we can calculate and extract the cluster distances programmatically. You can view the resulting plots below.

<img width="717" height="576" alt="Screenshot_20260825_153256_Chrome" src="https://github.com/user-attachments/assets/82145851-a74d-40b5-98d1-2033f8c76c5c" />
<img width="731" height="574" alt="Screenshot_20260825_153328_Chrome" src="https://github.com/user-attachments/assets/6aabf3c1-c5ce-4847-a733-93b345bf0f5a" />
