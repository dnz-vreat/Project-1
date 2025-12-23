# Project-1
=
# Insurance Claim Prediction – Machine Learning Project

This project focuses on predicting insurance claims using supervised machine learning techniques on an imbalanced dataset.

The objective is to identify policyholders with a higher probability of filing a claim, while properly handling class imbalance and evaluating models with relevant metrics beyond accuracy.

---

## Dataset

The dataset contains customer, vehicle, and contextual information related to insurance policies, with a binary target variable indicating whether a claim occurred.

Key characteristics:
- Strong class imbalance (minority class ≈ claims)
- Mixed numerical and categorical variables
- Tabular insurance data

---

## Methodology

The project follows a structured machine learning pipeline:

1. **Data exploration**
   - Dataset structure, missing values, imbalance analysis
   - Basic visualizations and correlations

2. **Preprocessing**
   - Imputation of missing values
   - Scaling of numerical features
   - One-hot encoding of categorical variables
   - Train / test split with no data leakage

3. **Baseline model**
   - Logistic Regression with `class_weight="balanced"`
   - Evaluation using Recall and F1-score for the claim class

4. **Advanced models**
   - Decision Trees
   - Random Forest (feature importance analysis)
   - Ensemble methods (Bagging, Voting)
   - Gradient Boosting to capture non-linear interactions

5. **Dimensionality reduction**
   - PCA used for exploratory analysis and interpretation

6. **Model evaluation**
   - Comparison using precision, recall, F1-score
   - Analysis of overfitting and underfitting
   - Discussion of model limitations

---

## Key Results

- Linear models provide a strong baseline but struggle with false positives.
- Tree-based and ensemble models better capture non-linear relationships.
- Claim risk is driven by multiple weak signals rather than a single dominant feature.
- Ensemble methods offer the best trade-off between performance and robustness.
- Gradient Boosting highlights the importance of handling class imbalance explicitly.

---

## Reference

The use of Gradient Boosting is motivated by:
- Friedman, J. H. (2001). *Greedy Function Approximation: A Gradient Boosting Machine*. Annals of Statistics.

---

## Files

- `Projet_Machine_Learning_final.ipynb` : final notebook containing the full analysis and results.

---

## Author

Machine Learning project – ESILV  
