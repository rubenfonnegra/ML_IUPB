# 🎲 Semana 8: Density-Based Clustering

<span class="badge badge-blue">🌊 Mean Shift</span>
<span class="badge badge-green">🫧 DBSCAN</span>

---

## 🎯 Objectives

- Understand the concept of density-based clustering.
- Explain how Mean Shift identifies clusters by searching for high-density regions.
- Understand how DBSCAN forms clusters based on density and neighborhood relationships.
- Identify the main parameters that control Mean Shift and DBSCAN.
- Recognize the differences between centroid-based and density-based clustering approaches.
- Implement and visualize Mean Shift and DBSCAN using Scikit-learn.

---

## 📌 Topics

- 🌊 Mean Shift
  - Density-based clustering
  - Searching for high-density regions
  - Kernel Density Estimation (KDE)
  - Moving points toward density peaks
  - Bandwidth
  - Automatic estimation of the number of clusters
  - Advantages and limitations

- 🫧 DBSCAN
  - Density-Based Spatial Clustering of Applications with Noise
  - Neighborhoods and density
  - Core points
  - Border points
  - Noise and outliers
  - `eps` parameter
  - `min_samples` parameter
  - Advantages and limitations

- 🔎 Comparing Clustering Approaches
  - K-Means vs. Mean Shift vs. DBSCAN
  - Centroid-based vs. density-based clustering
  - Number of clusters
  - Irregular cluster shapes
  - Noise and outlier detection
  - Choosing an appropriate clustering algorithm

---

## 🧠 Activities

- 💬 Discuss situations where clusters do not have a circular or clearly separated structure.
- 🌊 Visualize how Mean Shift moves candidate points toward regions of higher density.
- 🐍 Implement Mean Shift using Scikit-learn.
- 🔍 Explore how changing the `bandwidth` affects the clusters detected by Mean Shift.
- 🫧 Implement DBSCAN using Scikit-learn.
- 🧪 Experiment with different values of `eps` and `min_samples`.
- 📊 Visualize core points, border points, clusters, and noise identified by DBSCAN.
- ⚖️ Compare K-Means, Mean Shift, and DBSCAN on the same dataset.
- 📝 Complete a short quiz about density-based clustering.

---

> **💡 Weekly Challenge**
>
> Imagine you have a dataset containing the geographical locations of thousands of taxi pickups in a city. You do not know how many important pickup zones exist, and some locations may correspond to isolated or unusual trips.
>
> **Questions:**
>
> - Why might K-Means be difficult to use in this scenario?
> - How could Mean Shift identify important pickup zones?
> - How could DBSCAN distinguish dense pickup areas from isolated locations?
> - What would happen if you increased the value of `eps` in DBSCAN?
> - Which algorithm would explicitly identify some observations as noise?