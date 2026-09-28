# 📊 Semana 8: Clustering Evaluation Metrics

<span class="badge badge-blue">🎲 Clustering</span>
<span class="badge badge-green">📊 Model Evaluation</span>

## 🎯 Objectives

- Understand why clustering models require specific evaluation strategies.
- Differentiate between internal and external clustering evaluation metrics.
- Explain how Inertia measures cluster compactness.
- Interpret the Silhouette Score as a measure of cohesion and separation.
- Understand how Adjusted Rand Index (ARI) and Normalized Mutual Information (NMI) compare predicted clusters with known labels.
- Use clustering metrics to compare different algorithms and parameter configurations.

## 📌 Topics

- 📊 Evaluating Clustering Models
  - Challenges of evaluating unsupervised learning
  - Internal vs. external evaluation
  - Cluster cohesion and separation
  - The role of ground-truth labels
  - Comparing clustering solutions

- 🎯 Inertia
  - Within-cluster distances
  - Cluster compactness
  - Within-Cluster Sum of Squares (WCSS)
  - Interpretation of lower inertia values
  - Relationship with K-Means
  - Elbow Method
  - Limitations when comparing different numbers of clusters

- 👤 Silhouette Score
  - Intra-cluster cohesion
  - Inter-cluster separation
  - Silhouette coefficient
  - Values from -1 to 1
  - Interpretation of positive, near-zero, and negative values
  - Evaluating clustering without ground-truth labels
  - Handling noise in density-based clustering

- 🔀 Adjusted Rand Index (ARI)
  - Comparing predicted clusters with known labels
  - Pairwise agreement between partitions
  - Correction for agreement by chance
  - Interpretation of ARI values
  - Independence from cluster label names

- 🔗 Normalized Mutual Information (NMI)
  - Shared information between cluster assignments and known labels
  - Mutual information
  - Normalization
  - Interpretation of NMI values
  - Comparing different clustering solutions

- ⚖️ Choosing a Clustering Metric
  - Inertia vs. Silhouette Score
  - Internal vs. external metrics
  - When ground-truth labels are available
  - When ground-truth labels are unavailable
  - Using multiple metrics for model evaluation


## 🧠 Activities

- 💬 Discuss why Accuracy cannot normally be used directly to evaluate clustering models.
- 🎯 Calculate and compare Inertia for different numbers of K-Means clusters.
- 📉 Use the Elbow Method to explore an appropriate value of **k**.
- 👤 Calculate the Silhouette Score for different clustering solutions.
- 🐍 Compute ARI and NMI using Scikit-learn.
- 🔍 Compare K-Means, Mean Shift, and DBSCAN using appropriate clustering metrics.
- 🫧 Explore how DBSCAN noise points affect clustering evaluation.
- 📊 Build a comparison table containing Inertia, Silhouette, ARI, and NMI when applicable.
- 📝 Interpret the metrics and discuss whether they agree about the quality of the clustering solution.


> **💡 Weekly Challenge**
>
> Three clustering algorithms — **K-Means, Mean Shift, and DBSCAN** — are applied to the same dataset.
>
> You have the original class labels available **only for evaluation purposes**.
>
> **Questions:**
>
> - Which metrics can evaluate the clusters without using the original labels?
> - Which metrics require the original labels?
> - Can Inertia be meaningfully applied to every clustering algorithm?
> - What does a Silhouette Score close to **1** suggest?
> - What would a high ARI and high NMI indicate?
> - Could two clustering metrics disagree about which solution is better? Why?