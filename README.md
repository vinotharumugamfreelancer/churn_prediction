# Churn Prediction

This repository contains two key tasks for churn prediction:

### **Task 1: Exploratory Data Analysis (EDA) and Feature Engineering**
- **Notebook**: `eda.ipynb`
- This notebook includes:
  - Exploratory Data Analysis to understand the dataset.
  - Feature Engineering to prepare the dataset for model building.

### **Task 2: Model Building and Prediction**
- **Notebook**: `churn_pred.ipynb`
- This notebook includes:
  - Model training and evaluation.
  - Prediction and analysis of churn outcomes.

---

## **How to Run the Notebooks**

1. **General Instructions**:
   - Follow a **top-down approach**, executing each cell sequentially from the beginning of the notebook.

2. **Pre-run Output**:
   - The notebooks include outputs of previous runs.
   - If you need to re-run them, update the dataset paths as described below.

---

### **Data Path Configuration**

1. **For `eda.ipynb`**:
   - Replace the path for `challenge_dataset` (uploaded in this repository).
   - This will generate:
     - `cleaned_challenge_dataset` (processed version).
     - `final_challenge_dataset` (final dataset for modeling).

2. **For `churn_pred.ipynb`**:
   - If skipping EDA, replace the path for `final_challenge_dataset` directly in this notebook to load the processed dataset.

---

## **Output Files**
- The output datasets (`cleaned_challenge_dataset` and `final_challenge_dataset`) are automatically created during the execution of `eda.ipynb`.

---

### **Prerequisites**
- Ensure you have the required Python packages installed that are used in import statements.
