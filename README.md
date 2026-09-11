Smart Cart Customer Clustering 
A unsupervised machine learnig project using "KMeans" and "Agglomerative Hierarchical Clustering"-
Technique to identify customer segmentation

1. **Preprocessing & Feature Engineering**:
   - Categorical feature transformation using `OneHotEncoder`.
   - Feature standardization via `StandardScaler` to bring variables onto a uniform scale.
2. **Dimensionality Reduction**:
   - Principal Component Analysis (`PCA`) to compress high-dimensional feature spaces while preserving variance.
3. **Optimal Cluster Selection**:
   - **Elbow Method**: Programmatic knee/elbow detection using `KneeLocator`.
   - **Silhouette Analysis**: Cluster separation and cohesion evaluation using `silhouette_score`.
4. **Comparative Modeling**:
   - **K-Means Clustering**: Partitioning data into centroid-based groups.
   - **Agglomerative Clustering**: Hierarchical tree-based clustering to cross-validate groupings.
5. **Visualization**:
   - Cluster scatter plots, elbow curves, and correlation visualizations via `matplotlib` and `seaborn`.

     ## Tech Stack & Dependencies

**Language**: Python 3.x
 **Core Libraries**: `pandas`, `matplotlib`, `seaborn`
 **Machine Learning**: `scikit-learn` (`StandardScaler`, `OneHotEncoder`, `PCA`, `KMeans`, `AgglomerativeClustering`, `silhouette_score`)
 **Optimization**: `kneed`
