# Forest-Cover-Type-Classification
## Project Overview
This project tackles multi-class classification using the UCI Covertype Dataset
The goal is to predict forest cover type (7 categories) from cartographic and environmental features such as elevation, slope, soil type, and distance to hydrology/roadways.
We compare Random Forest and XGBoost models, evaluate their performance, and analyze feature importances.

---

## Dataset
- Source: UCI Machine Learning Repository
- Name: Covertype Dataset
- Instances: 581,012
- Features: 54 (10 quantitative, 44 binary indicators)
- Target: Cover_Type (7 forest cover categories)

---

## Workflow
1. Data Preprocessing
  - Identify continuous & categorical variables
  - Standardize continuous features using StandardScaler
  - Stratified train/test split (80/20)
2. Model Training
  - Random Forest Classifier
  - XGBoost Classifier (multi-class softmax)
3. Evaluation
  - Accuracy, Precision, Recall, F1-score
  - Confusion Matrix
  - Feature Importances
4. Hyperparameter Tuning
  - GridSearchCV for Random Forest (n_estimators, max_depth, min_samples_split)

---

## Results
1. Random Forest
  - Accuracy: 95.38%
2. XGBoost
  - Accuracy: 90.8%

---

## Tools & Libraries
- Python
- Pandas / NumPy – Data Handling
- Scikit-learn – Preprocessing, Modeling, Evaluation
- XGBoost – Gradient Boosted Trees
- Matplotlib / Seaborn – Visualization
- ucimlrepo – Dataset Fetching

Hyperparameter Tuning

GridSearchCV for Random Forest (n_estimators, max_depth, min_samples_split
