# Introduction to Machine Learning: Laboratory Portfolio

A comprehensive collection of machine learning algorithms and workflows implemented during the "Introduction to ML" course. This repository showcases practical applications of fundamental ML concepts, ranging from classic graph algorithms to advanced ensemble methods.

## 👥 Team & Collaboration
This repository was developed in collaboration with [Classmate's Name](https://github.com). 
* **My Core Contributions:** Model architecture design (neural networks), hyperparameter tuning, model evaluation, and metric analysis (ROC/AUC, Confusion Matrices).
* **Partner's Contributions:** Initial data preprocessing, exploratory data analysis (EDA), and baseline model implementations.

## 🛠️ Tech Stack & Libraries
* **Core Language:** Python 3.x
* **Data Libraries:** NumPy, Pandas
* **Machine Learning:** Scikit-Learn
* **Visualization:** Matplotlib, Seaborn

---

## 📂 Project Structure & Laboratory Works

### 🏛️ 01. Minimum Spanning Tree via Prim's Algorithm
* **Topic:** Graph Theory & Basic Python Environment
* **Objective:** Construct a Minimum Spanning Tree (MST) from an undirected weighted graph G(V, E) using Prim's algorithm.
* **Key Takeaway:** Successfully implemented a greedy optimization approach from scratch without external ML libraries, demonstrating solid algorithmic foundations.

### 📊 02. Naive Bayes Classification
* **Topic:** Probabilistic Classification Models
* **Data:** `sklearn.datasets.make_moons` & `load_digits` (pre-processed for non-negative values)
* **Models:** GaussianNB vs. MultinomialNB
* **Key Findings:** 
  * `GaussianNB` performed best on continuous decision boundaries (`make_moons`).
  * `MultinomialNB` excelled in discrete feature spaces (`load_digits`).
  * No overfitting observed; training and validation accuracies remained closely aligned.

### 🧠 03. Neural Networks for Data Classification
* **Topic:** Deep Learning Foundations & Model Evaluation
* **Data:** Moons and Digits datasets.
* **Tasks:** Investigating hidden layer neuron capacity and its impact on classification quality.
* **Metrics Used:** Confusion Matrix, Precision, Recall, F1-Score, PR-Curves, ROC-AUC.
* **Key Findings:** Tuning the hidden layer architecture achieved a stable data distribution and high evaluation metrics without overtraining.

### 📍 04. Unsupervised Learning: Data Clustering
* **Topic:** Synthetic Data Clustering and Metric Analysis
* **Data:** `make_blobs`, `make_circles`
* **Evaluation Metrics:** Estimated Number of Clusters, Adjusted Rand Index, Silhouette Coefficient, Davies–Bouldin Index.
* **Key Findings:** Comparison of alternative models with varying parameters and distance metrics confirmed stable cluster separation matching the synthetic ground truth.

### 🚀 05. Ensemble Methods: Gradient Boosting
* **Topic:** Advanced Regression via Model Ensembles
* **Method:** `GradientBoostingRegressor`
* **Data:** `sklearn.datasets.load_diabetes`
* **Analysis:** Computed and compared Accuracy, Bias, and Variance trade-offs between individual models and the ensemble.
* **Key Findings:** Verified that ensemble methods significantly outperform individual predictors by reducing variance while maintaining low bias.

---

## 🚀 How to Run the Code
1. Clone the repository:
   ```bash
   git clone https://github.com
   ```
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib scikit-learn seaborn
   ```
3. Open any `.ipynb` file in Jupyter Lab/Notebook or VS Code to explore the experiments.
