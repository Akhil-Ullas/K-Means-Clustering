📌 K-Means Clustering — Core Concept and Working Mechanism

K-Means is a partition-based clustering algorithm that groups data into K clusters based on similarity.

The algorithm iteratively:

Assigns each point to the nearest cluster centroid

Recomputes centroids based on assigned points

Repeats until cluster assignments stabilize

The objective is to:

• minimize within-cluster variance
• maximize separation between clusters

It provided a strong foundation for understanding clustering stability, compactness, and interpretability.

✔ Key Concepts Explored in the Module

• Choosing the optimal value of K
• Effect of scaling and normalization on distance-based clustering
• Cluster inertia and compactness
• Sensitivity to centroid initialization (k-means++)
• Convergence behavior and stopping conditions

I also evaluated clustering outcomes using:

• Elbow Method
• Silhouette Score
• Practical interpretability across segments

rather than relying only on mathematical metrics.

✔ Applications Where K-Means Proved Insightful

• Customer segmentation
• Market behavior grouping
• User activity pattern discovery
• Outlier and anomaly identification
• Feature grouping for ML pipelines

These exercises helped connect clustering outcomes to real-world analytical contexts.

✔ Advantages Observed

• Simple, fast, and scalable for large datasets
• Works well when clusters are compact and well-separated
• Easy to visualize and interpret
• Useful for exploratory insight generation

✘ Limitations Acknowledged

• Requires pre-defining the number of clusters (K)
• Sensitive to outliers and noisy data
• Performs poorly on non-spherical clusters
• Strongly affected by feature scaling
• Cluster results depend on initialization

These challenges encouraged a more critical and experiment-driven approach to clustering.
