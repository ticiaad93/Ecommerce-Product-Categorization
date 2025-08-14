# Notebooks

This folder contains the Jupyter/Colab notebook implementing the end-to-end  
**hierarchical product categorization pipeline** for an e-commerce dataset.

## 📜 Notebook Details
- **File:** `ecommerce_product_categorization.ipynb`
- **Purpose:** Train and evaluate machine learning models for:
  - Top-level category prediction (Voting Ensemble: Logistic Regression + Random Forest + LightGBM)
  - Bottom-level category prediction (Ridge Classifier)
- **Features:**
  - Text preprocessing with TF-IDF
  - Class imbalance handling with SMOTE
  - Model evaluation with Weighted F1-score
- **Output:** Final predictions stored in Parquet format for deployment/testing

## ⚠️ Dataset Requirement
The notebook requires a private dataset (see `../Data/README.md` for details).
Update file paths before running locally or in Google Colab.
