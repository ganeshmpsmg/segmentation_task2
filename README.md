# 🛒 PRODIGY_ML_02 — K-Means Customer Segmentation

<p align="center">
  <img src="https://img.shields.io/badge/Internship-Prodigy%20InfoTech-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Task-02-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Algorithm-K--Means%20Clustering-green?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Python-3.x-yellow?style=for-the-badge&logo=python"/>
</p>

---

##  Task Description

> **Create a K-Means clustering algorithm to group customers of a retail store based on their purchase history.**

**Internship:** Prodigy InfoTech — Machine Learning
**Task:** 02
**Dataset:** [Mall Customer Segmentation — Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

---

## 📁 Project Structure

```
PRODIGY_ML_02/
│
├── 📓 Step_01_Import_Libraries.ipynb
├── 📓 Step_02_Load_Dataset.ipynb
├── 📓 Step_03_EDA.ipynb
├── 📓 Step_04_Preprocessing.ipynb
├── 📓 Step_05_Find_Optimal_K.ipynb
├── 📓 Step_06_Train_KMeans.ipynb
├── 📓 Step_07_Visualize_Clusters.ipynb
├── 📓 Step_08_Analysis_and_Save.ipynb
│
├── 📄 Mall_Customers.csv              ← Download from Kaggle (see below)
├── 📄 submission.csv                  ← Final output with cluster labels
├── 📄 requirements.txt                ← Python dependencies
└── 📄 README.md                       ← This file
```

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/sentiment-analysis.git
cd 2_ml.ipynb
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Download the Dataset
- Visit 👉 [https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- Download **`submission.csv`**
- Place it in the **root project folder**

### 4️⃣ Run the Notebooks (in order)
```bash
jupyter notebook
```
Open and run **Step_01 → Step_08** in sequence.

---

## 📊 Step-by-Step Breakdown

| Step | Notebook | Description |
|:----:|----------|-------------|
| 01 | `Step_01_Import_Libraries` | Import numpy, pandas, sklearn, matplotlib, seaborn |
| 02 | `Step_02_Load_Dataset` | Load CSV, rename columns, preview data |
| 03 | `Step_03_EDA` | Distributions, pairplot, correlation heatmap |
| 04 | `Step_04_Preprocessing` | Feature selection + StandardScaler normalization |
| 05 | `Step_05_Find_Optimal_K` | Elbow Method + Silhouette Score → K = 5 |
| 06 | `Step_06_Train_KMeans` | Train K-Means (k-means++ init), attach labels |
| 07 | `Step_07_Visualize_Clusters` | 2D scatter, 3D plot, boxplots, gender chart |
| 08 | `Step_08_Analysis_and_Save` | Business insights + save clustered CSV |

---

## 🎯 Results — 5 Customer Segments

| Cluster | Income Level | Spending Level | Customer Profile | Recommended Strategy |
|:-------:|:------------:|:--------------:|:----------------|:--------------------|
| 0 | Low | Low | Budget-conscious shoppers | Discounts & value deals |
| 1 | High | Low | Rich but reluctant spenders | Premium loyalty rewards |
| 2 | Medium | Medium | Average balanced shoppers | Seasonal promos |
| 3 | Low | High | Impulsive low-income shoppers | Trendy budget products |
| **4 ⭐** | **High** | **High** | **Ideal VIP customers** | **Exclusive VIP programs** |

---

## 📈 Key Visualizations Generated

- `eda_distributions.png` — Gender, Age, Income distributions
- `pairplot.png` — Feature relationships
- `correlation_heatmap.png` — Correlation between features
- `optimal_k.png` — Elbow curve + Silhouette scores
- `customer_clusters_2D.png` — Final 2D cluster scatter plot
- `customer_clusters_3D.png` — 3D cluster visualization
- `cluster_boxplots.png` — Feature spread per cluster
- `gender_per_cluster.png` — Gender breakdown per cluster

---

## 🛠️ Technologies Used

| Library | Purpose |
|---------|---------|
| `pandas` | Data loading and manipulation |
| `numpy` | Numerical computations |
| `scikit-learn` | KMeans, StandardScaler, silhouette_score |
| `matplotlib` | Plotting and visualization |
| `seaborn` | Statistical visualizations |
| `jupyter` | Notebook environment |

---

## 📄 Output File — submission.csv

`submission.csv` contains the original dataset with two added columns:
- **`Cluster`** — Numeric cluster ID (0 to 4)
- **`Cluster_Label`** — Human-readable label (e.g., High Income High Spend)

---

## 👤 Author

**Ganesh MP**
🎓 Machine Learning Intern — Prodigy InfoTech
🔗 [https://www.linkedin.com/in/ganesh-mp444?utm_source=share_via&utm_content=profile&utm_medium=member_android] [https://github.com/ganeshmpsmg/ganeshmpsmg.github.io](https://github.com/YOUR_USERNAME)

---
> Please download it from the [dataset page](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python).
