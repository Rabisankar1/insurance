# 🏥 Insurance Charges Prediction & Analysis

## 📌 Project Overview

This project analyzes an insurance dataset to understand how different factors (like age, BMI, smoking habits, etc.) affect medical insurance charges. It also uses statistical methods such as **Pearson Correlation** to identify relationships between variables.

---

## 📊 Dataset Features

The dataset includes the following key features:

* **age** → Age of the individual
* **sex / is_female** → Gender
* **bmi** → Body Mass Index
* **children** → Number of dependents
* **smoker / is_smoker** → Smoking status
* **region** → Residential area
* **charges** → Medical insurance cost (target variable)

---

## ⚙️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* SciPy
* Scikit-learn

---

## 🔍 Key Analysis Performed

* Data Cleaning & Preprocessing
* Feature Engineering (Dummy Variables)
* Pearson Correlation Analysis
* Sorting features based on impact on insurance charges

---

## 📈 Sample Code (Correlation)

```python
from scipy.stats import pearsonr

correlations = {
    feature: pearsonr(df_cleaned[feature], df_cleaned['charges'])[0]
    for feature in selected_features
}
```

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Open the notebook:

```bash
jupyter notebook insurance.ipynb
```

3. Run all cells step by step

---

## 📌 Results & Insights

* Smoking has a strong positive correlation with charges
* BMI and age also significantly impact insurance cost
* Region has comparatively lower influence

---

## 📎 Future Improvements

* Add Machine Learning models (Linear Regression, Random Forest)
* Improve visualization (heatmaps, plots)
* Deploy as a web app

---

## 🙌 Author

**Rabisankar Pradhan**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
