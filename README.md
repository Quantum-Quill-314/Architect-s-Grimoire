# 🧠 Neuro-Computational Alchemy: Dopamine D2 Receptor Classification

> *"Where the rigid mathematics of algorithms meet the delicate chemistry of the human mind."*

[![Python](https://img.shields.io/badge/Python-3.8+-8A2BE2?style=for-the-badge&logo=python&logoColor=white)](#)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-9370DB?style=for-the-badge&logo=jupyter&logoColor=white)](#)
[![Machine Learning](https://img.shields.io/badge/Machine_Learning-Scikit_Learn-D8BFD8?style=for-the-badge&logo=scikit-learn&logoColor=black)](#)

Welcome to the digital crucible where molecular biology is decoded through machine learning. This repository houses the research, data processing, and predictive modeling pipeline designed to classify drug responses—specifically agonists and antagonists—targeting the **Dopamine D2 receptor**, utilizing the ChEMBL dataset.

## 📜 Table of Contents
- [Project Architecture](#-project-architecture)
- [The Data Pipeline](#-the-data-pipeline)
- [Visual Symphony (EDA)](#-visual-symphony-eda)
- [The Arena of Models](#-the-arena-of-models)
- [Authors](#-authors)

---

## 🏛️ Project Architecture

Our methodology is divided into three distinct phases, each meticulously documented within its respective Jupyter Notebook:

1. **`Data Pre-Processing.ipynb`**
   The foundation. Here, raw ChEMBL data is cleaned and standardized. We avoid mathematically crushing physical dimensions unnecessarily, opting for precise scalings that allow our algorithms to draw optimal decision boundaries without losing the delicate reality of features like `AlogP` and `Molecular Weight`.
   
2. **`EDA.ipynb`**
   The exploration. This notebook contains the statistical visualizations that map the relationships between molecular properties and biological activity.
   
3. **`Model Training and Testing.ipynb`**
   The final judgment. We deploy an ensemble of algorithms—including Random Forests, Gradient Boosting Machines, Support Vector Classifiers, and K-Nearest Neighbors—to determine the champion model based on rigorous ROC-AUC and classification metrics.

---

## 🧬 The Data Pipeline

The dataset, culminating in `Processed DataFrame.csv`, has been engineered to capture the most critical molecular features:
* **Molecular Weight (MW)**
* **AlogP** (Partition Coefficient)
* **Ligand Efficiency BEI**
* **pChEMBL Values**

*Note: The dataset features have been carefully balanced to ensure our models do not let massive physical dimensions overshadow the finer, decimal-scale chemical properties.*

---

## 🌌 Visual Symphony (EDA)

Data without visualization is simply noise. Within the repository, you will find a curated collection of graphical insights:

* **`heatmap_correlation.png`**: The web of relationships between our chemical features.
* **`violin_alogp_activity.png` & `boxplot_mw_activity.png`**: Density distributions mapping how AlogP and Molecular Weight separate the activity classes.
* **`kde_mw_alogp.png`**: The topological landscape of our feature space.
* **`scatter_mw_lei.png`**: The intersection of weight and ligand efficiency.

---

## ⚔️ The Arena of Models

To predict the D2 receptor interactions, we cast several algorithms into the arena. Our evaluation metrics go beyond mere accuracy, utilizing the **Comparative ROC Curve** (`comparative ROC Curve.png`) to measure true predictive power and area under the curve (AUC). 

The models are evaluated on their ability to discern the subtle, almost agathokakological differences between a molecule that activates a receptor and one that blocks it.

---

## ✒️ Authors

**Dhawal Mehrotra** 
**Bhavya Anup Sharma** 
*Symbiosis Institute of Technology*
