# Machine Learning Models Portfolio

**Author:** Enrico Miguel Veloso  
**Course:** DSA#4155 - Artificial Intelligence  
**Institution:** University of Santo Tomas - College of Science

---
## 📌 Overview
This repository contains a comprehensive collection of machine learning implementations ranging from fundamental regression techniques to advanced ensemble methods and unsupervised learning. Each notebook demonstrates practical application of theoretical concepts using real-world datasets, with detailed explanations, visualizations, and performance evaluations.

---
## 📁 Repository Structure
- Ordinary Least Squares Regression.md
- Linear Probability Model.md
- Logistic Regression and General Linear Models (GLM).md
- Regularization and Advance Classification.md
- Machine Learning Model Comparison.md
- Ensemble Methods and Advance Classifications.md
- Boosting Methods and Advance Ensemble Learning.md
- K-Means vs DBSCAN.md
- Dimensionality Reduction.md
- Market Basket Analysis.md

---
## 📚 Models & Techniques Covered
### Regression Models
| Model | Dataset | Key Techniques |
|-------|---------|----------------|
| **Ordinary Least Squares (OLS)** | Auto MPG | Linear regression, VIF analysis, multicollinearity detection |

### Classification Models (Linear & Generalized)
| Model | Dataset | Key Techniques |
|-------|---------|----------------|
| **Linear Probability Model (LPM)** | Adult Income (Census 1994) | Binary classification, probability bounds analysis |
| **Logistic Regression** | Adult Income (Census 1994) | GLM, odds ratios, statistical inference |

### Regularization Methods
| Model | Techniques |
|-------|------------|
| **Regularized Linear Models** | Lasso (L1), Ridge (L2), Elastic Net, Cross-validation tuning |

### Tree-Based & Ensemble Methods
| Model | Techniques |
|-------|------------|
| **Decision Trees** | Recursive partitioning, feature importance, pruning, visualization |
| **Bagging** | Bootstrap aggregation, variance reduction |
| **Random Forest** | Feature randomization, parallel ensemble, out-of-bag error |
| **AdaBoost** | Adaptive boosting, sample weighting, weak learners |
| **Gradient Boosting** | Residual fitting, sequential error correction |

### Unsupervised Learning
| Model | Dataset | Techniques |
|-------|---------|------------|
| **K-Means Clustering** | Credit Card Dataset | Elbow method, silhouette analysis, centroid interpretation |
| **DBSCAN** | Credit Card Dataset | Density-based clustering, eps & min_samples tuning, noise detection |
| **PCA & Dimensionality Reduction** | Global Country Data | Principal components, explained variance, biplots, t-SNE, UMAP |

### Association Rule Mining
| Model | Dataset | Techniques |
|-------|---------|------------|
| **Market Basket Analysis** | 2022 Philippine Election Data | Apriori algorithm, support/confidence/lift metrics, rule mining |

---
## 📊 Dataset Descriptions
| Dataset | Source | Size | Target Variable |
|---------|--------|------|-----------------|
| **Auto MPG** | UCI ML Repository | 398 rows, 9 features | Fuel efficiency (MPG) |
| **Adult Income** | OpenML (v2) | 48,842 rows, 15 features | Income >$50K |
| **Credit Card Dataset** | Kaggle | 8,636 rows, 6 features | Customer segments |
| **Global Country Data 2023** | Kaggle | 195 rows, 10+ features | Development indicators |
| **Philippines Election 2022** | Figshare (CC BY 4.0) | Province-level | Senatorial voting patterns |

---
## 🔧 Technologies Used
### Core Libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
