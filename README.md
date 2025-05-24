# Financial-Fraud-Detection-Model

A simple financial fraud detection model, that can be used to predict/detect fraudulent transactions. It has been trained on over 6 million financial transactions.

---

### Dataset:
`https://www.kaggle.com/datasets/sriharshaeedala/financial-fraud-detection-dataset/data`

The data was directly downloaded and used to create this model. It can also be used simply via the Kaggle API.

I do not claim ownership of this dataset.

---

### Dependencies and libraries

The only external library required was xgboost. Installed with a simple line of code `!pip install xgboost`.

Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn are used.

---
### Models:

The following models are trained to choose the best among them:
#### 1. Random Forest (best performing)
- F1 -> 84.46% (highest)
- Run time -> Couple of minutes (fastest)

#### 2. XGBoost
- F1 -> 84.46% (highest)
- Run time -> Couple of minutes (fastest)

#### 3. KNN
- F1 -> 66.58% (highest)
- Run time -> 11 hours (approx)

#### 4. SVM (XXX Dropeed XXX)
- F1 -> N/A
- Run time -> Failure at 19 hours (approx). The kernel stopped.

---
### Findings:

Random Forest performed best based on its F1-score of 84.46%. It outperforms the F1 of the other models used here and also other popular models for this dataset.
Based on the F1 scores, this model has a 68.9% boost in performance over the best-performing model of the most popular solution to the dataset on kaggle found under `https://www.kaggle.com/code/adityashakya2454/fraud-detection`
