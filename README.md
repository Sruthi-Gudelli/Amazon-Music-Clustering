# Music Clustering & Genre Classification

A machine learning project that uses the K-Means clustering algorithm to group songs based on their acoustic features and classify them into distinct genres. This repository includes the complete source code and a presentation detailing the project's methodology, visualizations, and findings.

### 🚀 Project Overview

The goal of this project is to identify patterns in music data and automatically group similar tracks together. By analyzing unique audio characteristics, the K-Means algorithm discovers underlying structures in the dataset, effectively classifying songs into clusters that correspond to different musical genres.

### Key Components

*   **Problem Statement:** Defined the core challenges of automated music categorization and the limitations of manual tagging.
*   **Feature Analysis:** Evaluated critical audio attributes to determine how they influence song similarity.
*   **K-Means Clustering:** Implemented the clustering pipeline to group songs without prior label training.
*   **Visualizations:** Created multi-dimensional cluster plots to visualize how distinct the musical groupings are.

* * *

### ⚙️ Methodology & Approach

1.  **Feature Engineering:** Extracted and normalized key audio features to ensure equal weighting during clustering.
2.  **Optimal Cluster Selection:** Used evaluation techniques (such as the Elbow Method, Silhouette Score and Davies-Bouldin Index) to find the ideal number of genre clusters.
3.  **K-Means Modeling:** Partitioned the music dataset into K distinct, non-overlapping subgroups.
4.  **Cluster Evaluation:** Profiled each cluster to map the mathematical groupings to actual musical genres.

* * *

### 📊 Visualizations & Results

The project presentation (`AmazonMusicClustering.pptx`) contains detailed visual insights, including:

*   **Feature Distributions:** Graphical breakdowns of how musical features vary across the clusters.
*   **Cluster Scatter Plots:** Visual representations of the final song clusters showing how well the K-Means algorithm separated different genres.


