# Data Folder

This folder serves as a placeholder for the dataset used in this project.

## 📂 About the Dataset
The dataset was obtained from a **private e-commerce company** and contains product listings annotated with:
- **Top-level category IDs** (e.g., `home-decor`)
- **Bottom-level category IDs** (e.g., `home-decor-vases`)
- **Product titles** and descriptions
- **Tags** (short keywords or phrases)
- Additional structured attributes (e.g., material, recipient, occasion)

Due to confidentiality agreements, **the dataset cannot be shared publicly**.

## 🔒 Data Privacy Notice
This dataset contains proprietary business information and is bound by non-disclosure agreements (NDAs).  
As such, it has been **excluded from this repository** in compliance with data privacy requirements.

## 🛠 How to Reproduce the Results
To replicate the experiments in this project, prepare your own dataset that follows a similar schema:
- CSV or Parquet format  
- One row per product listing  
- Columns for:
  - `top_category_id`
  - `bottom_category_id`
  - `title`
  - `description`
  - `tags`
  - Any relevant structured metadata

Ensure your dataset is cleaned, formatted, and split into **training** and **testing** sets as described in the main [project report](../Docs/Ecommerce_Product_Categorization_Report.pdf).

## ⚠️ Note
If you intend to run the provided notebook, update the dataset path variables to point to your **local** or **private cloud storage** copy of the data.

---
