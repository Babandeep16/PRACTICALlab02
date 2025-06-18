# Practical Lab 02: Multivariate Linear Regression, Non-Parametric Models, and Cross-Validation

Name- Babandeep
StudentID- 9001552
Course- Foundations of machine learning and frameworks

##  Objective

Build predictive models using the **Scikit-learn Diabetes Dataset** to estimate disease progression one year after baseline. Explore both **univariate** and **multivariate models**, including **polynomial regression**, **decision trees**, and **k-Nearest Neighbors**.

---

##  Models Implemented

###  Part 1: Data Processing and EDA
- Loaded dataset from `sklearn.datasets.load_diabetes()`
- Conducted exploratory data analysis (EDA)
  - Histograms, scatter plots, and correlation matrix
- No missing values; data standardized
- Train (75%) / Validation (10%) / Test (15%) split

###  Part 2: Univariate Polynomial Regression (Using BMI)
- Polynomial models trained from **degree 0 to 5**
- Best model: **Degree 5**, based on validation R²
- Evaluated using R², MAE, and MAPE
- Model equation displayed
- Curve plotted over train, val, test data
- Limitations and model discussion included

### Part 3: Multivariate and Non-Parametric Models
- **Polynomial Regression** (degree 2 and 3)
- **Decision Trees** (max_depth = 3 and 5)
- **k-Nearest Neighbors** (k = 3 and 7)
- Evaluation table using R², MAE, MAPE (val + test sets)
- Summary of best model and limitations

---

## Reproducibility

-  All code runs on standard `scikit-learn` dataset (static version also saved as CSV)
- `requirements.txt` file included
- Outputs include evaluation metrics, plots, and markdown explanations
- Notebook commits are clean and structured

---

##  File Structure
PRACTICALLAB02/
- PA2.ipynb # Final notebook
- requirements.txt # Environment dependencies
- README.md # Project summary

