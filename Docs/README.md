# Documentation

This folder contains the supporting documentation for the **E-commerce Product Categorization** project.

## 📄 Files
- **Ecommerce_Product_Categorization_Report.pdf**  
  Detailed academic/technical report describing:
  - Problem statement & business context
  - Dataset description (private, see `../Data/README.md`)
  - Methodology: TF-IDF vectorization, SMOTE balancing, model selection
  - Model architectures: Logistic Regression, Random Forest, LightGBM, Ridge
  - Evaluation metrics (Weighted F1-score)
  - Results: 
    - **Top-level classification:** Voting Ensemble → F1 = 0.91
    - **Bottom-level classification:** Ridge Classifier → F1 = 0.75
  - Limitations & future work

## 🔍 Usage
Refer to this report for:
- Understanding the machine learning pipeline
- Dataset schema & preprocessing steps
- Model performance comparisons

## 📌 Note
The dataset referenced in the report is **private** and cannot be shared publicly.  
For reproduction, please prepare your own dataset following the structure described in the report.
