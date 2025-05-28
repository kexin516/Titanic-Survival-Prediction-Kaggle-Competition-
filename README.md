# Titanic-Survival-Prediction

##  Overview

This project addresses the classic binary classification problem: predicting whether a passenger survived the Titanic disaster based on features like age, sex, ticket class, and family connections.

## Kaggle Competition

This project is built as a solution for the [Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic) competition on Kaggle. The goal is to build models that accurately predict passenger survival using the provided train and test datasets.

###  Highlights

- **EDA:** Explored data structure, set index, identified and manipulated missing values, and analyzed the distribution of the target and features
- **Feature Engineering:** Created features like `IsAlone`, `AgeBucket`, `RelativesOnboard`
- **Modeling Techniques:**  
  - Logistic Regression  
  - Random Forest  
  - Gradient Boosting  
  - Support Vector Classifier (SVC)  
  - Stacking Classifier
- **Evaluation:** 10-fold cross-validation, accuracy comparison, confusion matrix analysis
- **Kaggle Score:** `0.78468` (Public Leaderboard)

##  Tech Stack

- Python
- Pandas, NumPy
- scikit-learn
- Seaborn, Matplotlib
- XGBoost

##  Getting Started

1. Clone this repo:
```bash
git clone https://github.com/kexin516/Titanic-Survival-Prediction.git
