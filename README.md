# Credit Card Fraud Detection

## Description

This repository contains a single notebook, `CCFD.ipynb`, which demonstrates how to detect credit card fraud using a variety of machine learning models. It includes data preprocessing, handling class imbalance with SMOTE, and evaluation of model performance using precision, recall, F1-score, and ROC-AUC.

## Dataset

This notebook is built on the [Kaggle Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download). The dataset contains 284,807 anonymized credit card transactions, including 492 fraud cases (\~0.17%).

> **Note:** The dataset is not included in this repository due to size limits. Please download `creditcard.csv` manually from the Kaggle link above and place it in your working directory.

## Requirements

* Python 3.7+
* pandas
* numpy
* scikit-learn
* imbalanced-learn
* xgboost (optional)

Install dependencies:

```bash
pip install pandas numpy scikit-learn imbalanced-learn xgboost
```

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/Prudhvirajrekula/Creditcard-Fraud-Detection.git
   cd Creditcard-Fraud-Detection
   ```
2. Download `creditcard.csv` from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download) and place it in the same directory.
3. Open and run the notebook:

   ```bash
   jupyter notebook CCFD.ipynb
   ```
