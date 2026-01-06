# **GDG Task 3 — Unsupervised Learning & Advanced Supervised Learning**

Welcome to the GDG Task 3 repository!
This task is a comprehensive guide bridging **Unsupervised Learning** and advanced **Supervised Learning** techniques. It covers clustering algorithms using the Samsung Human Activity Recognition dataset and dives deep into classification, ensemble methods, and optimization using the Titanic dataset.

## **Key Topics Covered**

### **1. Unsupervised Learning (Clustering)**

*   **Dataset**: Samsung Human Activity Recognition (Sensor data).
*   **Algorithms**:
    *   **K-Means Clustering**: Grouping data based on centroids; using the **Elbow Method** for optimal $k$.
    *   **Agglomerative Clustering**: Hierarchical approach building clusters bottom-up; visualized with dendrograms.
    *   **Spectral & Divisive Clustering**: Theoretical exploration of graph-based and top-down clustering methods.
*   **Visualization & Metrics**:
    *   **PCA (Principal Component Analysis)**: Reducing dimensions for 2D/3D visualization.
    *   **Adjusted Rand Index (ARI)**: Evaluating clustering quality against ground truth.

### **2. Supervised Learning Expansion**

*   **Dataset**: Titanic Survival Prediction.
*   **Data Preprocessing**:
    *   Feature Extraction (e.g., Titles from names, Family size calculation).
    *   Handling Nulls and Encoding categorical variables.
*   **Decision Tree Classifier**:
    *   Building and Visualizing Decision Trees.
    *   Understanding **Overfitting vs. Underfitting** by tuning tree depth.
*   **Naive Bayes**:
    *   Implementing Gaussian Naive Bayes and comparing it with Decision Trees.

### **3. Ensemble Techniques**

*   **Bagging (Bootstrap Aggregating)**:
    *   **Random Forest**: Reducing variance by averaging multiple decision trees.
    *   **BaggingClassifier**: General bagging implementation.
*   **Boosting**:
    *   **AdaBoost**: Reducing bias by sequentially correcting errors of weak learners.
*   **Optimization with GridSearchCV**:
    *   Automating hyperparameter tuning to find the best model configuration.

### **4. Model Optimization & Pruning**

*   **Tree Pruning**:
    *   Implementing **Cost Complexity Pruning** (`ccp_alpha`) to simplify trees and improve generalization.
    *   Visualizing the trade-off between tree complexity and accuracy.
*   **Comparative Analysis**:
    *   Benchmarking Decision Trees, Naive Bayes, Random Forest, Bagging, and Boosting to determine the optimal model.
