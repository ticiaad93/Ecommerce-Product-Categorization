# Ecommerce-Product-Categorization


A machine learning pipeline for **hierarchical e-commerce product categorization**, predicting both top-level and bottom-level product categories from product metadata.  
Built with **TF-IDF**, **SMOTE**, and a **Voting Ensemble** of Logistic Regression, Random Forest, and LightGBM for top-level categories, and Ridge Classifier for bottom-level categories.

---

## 📊 Project Overview
- **Goal:** Automatically assign e-commerce products to their correct top and bottom categories.
- **Top-level classification:** Voting Ensemble → **F1-score = 0.91**
- **Bottom-level classification:** Ridge Classifier → **F1-score = 0.75**
- **Data type:** Structured + unstructured product metadata (titles, descriptions, tags)
- **Key challenges:** Class imbalance, high-dimensional sparse features, noisy text

