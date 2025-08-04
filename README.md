# 🏀 Predictive Model for Drafting College Basketball Players

This project develops a machine learning pipeline to predict whether college basketball players are likely to be drafted into the NBA. By leveraging historical NCAA player statistics, we apply clustering and classification techniques to uncover patterns and assist scouting decisions.

---

## 🎯 Objectives

- Identify key performance metrics associated with draft selection
- Cluster players based on their playing style and performance
- Build a predictive model to estimate the likelihood of being drafted
- Evaluate models across different dimensionality reductions (PCA)

---

## 📁 Project Structure

Predictive-Model-for-Drafting-College-Basketball-Players/

\```

Predictive-Model-for-Drafting-College-Basketball-Players/

├── data/          # Raw and preprocessed datasets

├── reports/        # Figures, plots, and model evaluation results

├── scripts/        # Utility functions and ML pipeline scripts

├── README.md        # Project documentation

\```

---

## 🧠 Methodology

### 1.  Data Preprocessing
- Combined multiple seasons of NCAA player stats
- Cleaned and filtered players with incomplete data
- Normalized key numeric features for fair comparison

### 2. Feature Engineering
- Selected features: height, weight, points, assists, rebounds, efficiency ratings
- Created composite metrics like shooting efficiency and usage rate

### 3. Dimensionality Reduction
- Applied **Principal Component Analysis (PCA)**:
  - Compared results with 2 vs 3 principal components
  - Visualized player clusters in reduced dimensions

### 4. Clustering
- Used **DBSCAN** and **K-Means** to discover player archetypes
- Evaluated clustering quality using **Silhouette Score** and **Elbow Method**
- Compared clusters with actual draft outcomes to identify "draft-heavy" clusters

### 5. Classification
- Binary target: Drafted (1) vs Not Drafted (0)
- Models used:
  - Logistic Regression
- Evaluated using Accuracy, Precision, Recall, and ROC-AUC

---

## 🛠️ Required Software

- R studio 

