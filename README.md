# Machine-Learning-Project
a complete portfolio of my Data Science &amp; Machine Learning projects.

# 📈 Salary Prediction Model: Data-Driven Compensation Strategy

## 🌟 Project Overview

This project focuses on developing a robust **Machine Learning model** to accurately predict employee salaries based on key professional features (Experience, Age, Education Level, and Job Title). The primary objective is to identify the best predictive model and leverage **Feature Importance** insights to inform fair and data-driven compensation policies.

## 🎯 Key Results & Business Impact

Three regression models were evaluated. The **Random Forest Regressor** demonstrated superior performance across all metrics:

| Metric | Random Forest (Best) | Decision Tree | Linear Regression |
| :--- | :--- | :--- | :--- |
| **$R^2$ Score** | **0.977** | 0.946 | 0.846 |
| **MAE** | **$3,153** | $7,489$ | $15,046$ |

* **Prediction Accuracy:** The Random Forest model achieved a near-perfect $\mathbf{R^2}$ of $\mathbf{0.977}$, meaning it explains **97.7%** of the variability in salary.
* **Minimal Error:** The average prediction error (**MAE**) is only **$3,153**, making the model highly reliable for internal salary benchmarking and auditing.

## 💡 Strategic Compensation Recommendations

Based on the **Feature Importance** analysis (where **Years of Experience** and **Age** were the dominant factors):

1.  **Experience-Driven Pay Structure:** Compensation policies should be heavily weighted towards **Years of Experience**. The salary scale must ensure significant and consistent raises tied directly to tenure to effectively **retain experienced talent** and maintain internal fairness.
2.  **Model as an Audit Tool:** The deployed Random Forest model can be used to **flag potential salary outliers** (employees paid significantly above or below the model's prediction), helping to proactively address pay inequity issues.
3.  **Job Title Standardization:** Use the predictive insights from specific job titles (e.g., Data Scientist) to establish clear, justifiable pay bands, promoting transparency across the organization.

## 🛠️ Technology Stack

* **Language:** Python 3.x
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Environment:** Google Colab
* **Version Control:** Git

## 📂 Repository Contents

* `Salary_Prediction_Project.ipynb`: Core notebook containing data cleaning, model training, and evaluation for the three models.
* `Salary_Data`: The original dataset used for analysis.

## Conclusion
* This project spent 4 days working on it includes coding, analysing, training, testing and pulling to Github.
* **Thank you for spending time reading and exploring my self-project.**
