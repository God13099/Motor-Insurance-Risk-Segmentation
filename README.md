# Motor Insurance Risk Segmentation & Claim Prediction

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Tool-Jupyter_Notebook-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)

## 📌 Project Overview
This project focuses on analyzing a motor insurance portfolio to enhance risk assessment strategies. By leveraging **unsupervised learning** for customer segmentation and **Generalized Linear Models (GLM)** for claim frequency prediction, we identify key risk drivers and distinct policyholder profiles.

The analysis provides actionable insights for insurance pricing and risk management, comparing Baseline (Poisson) and Alternative (Negative Binomial) models to handle overdispersion in claim counts.

## 🎯 Objectives
1.  **Customer Segmentation:** Group policyholders into distinct risk profiles using **K-Means Clustering**.
2.  **Risk Factor Analysis:** Identify significant variables (e.g., driver age, car power, history score) affecting claim frequency.
3.  **Predictive Modeling:** Build and compare statistical models to predict the number of claims (`claim_nb`), specifically addressing the "zero-inflated" and overdispersed nature of insurance data.

## 🛠 Technologies & Methods
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels
* **Key Techniques:**
    * **Clustering:** K-Means (Elbow Method, Silhouette Analysis)
    * **GLM Regression:** Poisson Regression (Baseline), Negative Binomial Regression (to handle overdispersion)
    * **Model Evaluation:** AIC, BIC, Log-Likelihood, Cross-Validation

## 📂 Repository Structure
```text
├── Project2.ipynb          # Main Jupyter Notebook containing data processing, modeling, and visualization
├── ABA Project 2.pdf       # Detailed business report with interpretation of results and conclusions
├── requirements.txt        # List of Python dependencies
└── README.md               # Project documentation
