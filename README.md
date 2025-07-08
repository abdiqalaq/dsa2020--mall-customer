# Clustering and Dimensionality Reduction on Mall Dataset

This repository contains a Jupyter Notebook that explores unsupervised learning techniques including K-Means and Hierarchical Clustering, along with dimensionality reduction techniques such as PCA and t-SNE.



## 📁 Project Structure

This notebook is divided into the following main tasks:

---

## 🔍 Task 1: Data Exploration & Preprocessing

- **Dataset loading and inspection**
  - Summary statistics (`mean`, `std`, etc.)
  - Missing value handling (if any)
  - Feature scaling using `StandardScaler` or `MinMaxScaler`

- **Data Visualization**
  - Pair plots to explore feature relationships
  - Histograms to show feature distributions

- **Analysis Questions**
  - Observed trends and feature relationships

---

## 📊 Task 2: K-Means Clustering

- K-Means implementation with various values of `k`
- **Elbow method** used to find optimal `k`
- 2D scatter plot of clusters (using PCA if needed)

- **Analysis Questions**
  - Optimal number of clusters from elbow curve
  - Interpretation of cluster characteristics

---

## 🌿 Task 3: Hierarchical Clustering

- Agglomerative clustering using different linkage methods:
  - `ward`, `average`, `complete`
- Dendrogram visualization

- **Analysis Questions**
  - Differences between K-Means and Hierarchical clusters
  - Best-performing linkage method

---

## 🔻 Task 4: Dimensionality Reduction (PCA)

- PCA to reduce dataset dimensions
- Explained variance ratio plot
- 2D scatter plot of first two principal components
- Cluster visualization over PCA plot

- **Analysis Questions**
  - Variance explained by the first two components
  - How PCA helps cluster visualization

---

## 🔷 Task 5: Dimensionality Reduction (t-SNE)

- t-SNE for 2D visualization
- Comparison with PCA plots

- **Analysis Questions**
  - Difference between t-SNE and PCA
  - Which technique shows clearer cluster separation

---

## ⭐ Bonus Task: Cluster Evaluation (Optional)

- Calculated **Silhouette Scores** for:
  - K-Means Clustering
  - Hierarchical Clustering
- Interpreted the quality of clustering using the scores


---

## 📌 Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 🔗 License

This project is for educational purposes only.
