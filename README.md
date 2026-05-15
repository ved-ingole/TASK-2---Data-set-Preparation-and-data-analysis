# 🩺TASK-2 - Diabetes Dataset Preparation & Feature Analysis

## VAUTECH IT SOLUTIONS - TASK 2

| | |
|---|---|
| **Intern** | Ved |
| **Domain** | Machine Learning |
| **Company** | VAUTECH IT SOLUTIONS |
| **Task** | Dataset Preparation & Feature Analysis |

---

# 📂 Dataset

- **Dataset Name:** PIMA Indians Diabetes Dataset
- **Source:** OpenML Repository
- **Loaded Using:** `fetch_openml()` from scikit-learn
- **Instances:** 768
- **Features:** 8 Input Features + 1 Target Column
- **Task Type:** Binary Classification
- **Target:** `0 = No Diabetes` / `1 = Diabetes`

---

# 🎯 Project Objectives

1. Load dataset using Python
2. Perform feature analysis
3. Identify important and irrelevant features
4. Detect feature correlation and redundancy
5. Analyze class imbalance
6. Visualize dataset patterns

---

# 🔁 Project Pipeline

## Step 1: Load Dataset
- Loaded PIMA Indians Diabetes Dataset using `fetch_openml()`
- Converted target labels into numeric values
- Renamed columns for better readability

---

## Step 2: Data Cleaning
- Identified invalid zero values in medical columns
- Replaced impossible values with `NaN`
- Filled missing values using median imputation

Columns cleaned:
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI

---

## Step 3: Dataset Exploration
- Checked dataset shape
- Displayed first few rows
- Examined data types
- Checked missing values

---

## Step 4: Statistical Analysis
- Generated descriptive statistics using `describe()`
- Calculated:
  - Mean
  - Median
  - Standard Deviation
  - Minimum & Maximum values

---

## Step 5: Feature Variance Analysis
- Calculated variance of numerical features
- Identified high variance and low variance features
- Used variance to understand feature importance

---

## Step 6: Correlation Analysis
- Created correlation matrix
- Detected relationships between features
- Identified highly correlated features
- Checked feature redundancy

---

## Step 7: Class Imbalance Analysis
- Counted diabetes vs non-diabetes samples
- Analyzed target distribution
- Verified dataset imbalance

---

## Step 8: Data Visualization
Created visualizations using:
- Histograms
- Count plots
- Correlation heatmaps

Visualizations helped in:
- Understanding feature distributions
- Identifying patterns
- Detecting correlations

---

# 📊 Key Findings

| Analysis | Observation |
|---|---|
| Most Important Feature | Glucose |
| Strong Correlation | BMI ↔ SkinThickness |
| Class Distribution | Slightly imbalanced |
| Dataset Type | Medical binary classification |

---

# 🛠️ Tools & Libraries

| Tool | Purpose |
|---|---|
| Python | Programming language |
| pandas | Data loading & manipulation |
| NumPy | Numerical operations |
| matplotlib | Data visualization |
| seaborn | Statistical visualization |
| scikit-learn | Dataset loading |

---

# 📁 Files

| File | Description |
|---|---|
| `diabetes_feature_analysis.ipynb` | Main notebook |
| `README.md` | Project documentation |
| `outputs/` | Saved graphs & charts |

---

# 📈 Visualizations Included

- Feature Distribution Histograms
- Correlation Heatmap
- Diabetes Class Distribution Plot
- Feature Variance Graph

---

# 🚀 How to Run

## 1. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 2. Run Jupyter Notebook

```bash
jupyter notebook
```

## 3. Open Notebook File

```bash
diabetes_feature_analysis.ipynb
```

---

# 📚 Dataset Citation

Smith, J. W., Everhart, J. E., Dickson, W. C., Knowler, W. C., & Johannes, R. S. (1988). PIMA Indians Diabetes Dataset. National Institute of Diabetes and Digestive and Kidney Diseases.

---

# 👨‍💻 Author

Ved

---

# ✅ Conclusion

This project focused on dataset preparation and feature analysis for the PIMA Indians Diabetes Dataset. Various statistical and visualization techniques were used to understand feature importance, feature relationships, and dataset imbalance. The project helped build strong foundational knowledge in data preprocessing and exploratory data analysis for machine learning.
