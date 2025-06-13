# 🧬 Transcriptomic Correlation and Clustering Analysis in Mouse Tissues

This project explores the **correlation structure** and **clustering patterns** within a transcriptomic dataset from two mouse tissues. By combining exploratory data analysis, correlation visualization, and clustering algorithms, we aim to uncover underlying biological structure and gene expression patterns.

---

## 📌 Objectives

- Explore gene expression correlations between samples and genes.
- Visualize inter-variable relationships using pairwise plots.
- Apply clustering methods to identify intrinsic groupings.
- Determine the optimal number of clusters using internal validation metrics.

---

## 🧪 Dataset

- **Type**: Transcriptomic measurements (gene expression levels)
- **Subjects**: Two mouse tissues
- **Format**: Matrix of expression values (samples × genes)

---

## 🧭 Workflow Overview

### 1. 🗂️ Data Loading and Exploration
- Import transcriptomic data from two mouse tissues.
- Brief summary statistics and inspection of the dataset structure.

### 2. 📊 Correlation Analysis with `pairs()`
- Use of the `pairs()` function to visualize pairwise correlations between genes.
- Identification of correlation patterns and expression similarities.

### 3. 🧩 Clustering with k-means and Hierarchical Methods
- Apply **k-means** clustering and **hierarchical clustering** to group similar expression profiles.
- Visual assessment of cluster separation and consistency.

### 4. 🔍 Cluster Validation with `clValid`
- Use of the `clValid` package to determine the optimal number of clusters.
- Evaluation based on internal validation measures (connectivity, Dunn index, silhouette width).

---

## 🛠️ Tools & Libraries

- `R`, `stats`, `graphics`, `clValid`
- Optional: `ggplot2`, `factoextra`, `dendextend`

---

## 📁 Repository Structure

