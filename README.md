[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sakshiblip/customer-churn-prediction/blob/main/feature_engineering_for_customer_churn_prediction.ipynb)

# Preventing Customer Churn with Feature Transformation 📉

This repository contains a specialized machine learning project focused on predicting customer attrition. By emphasizing advanced feature engineering and data transformation, this project builds a robust classification system to identify "at-risk" customers and help businesses implement proactive retention strategies.

## 📌 Project Overview
The primary goal of this project is to improve the predictive power of churn models through meticulous data preparation. It moves beyond simple model training to explore how feature scaling, categorical encoding, and class balancing (SMOTE) impact the model's ability to capture complex churn patterns.

## 🚀 Key Features
* **End-to-End Pipeline:** Implementation of `Scikit-learn Pipelines` for seamless data transformation and model training.
* **Advanced Feature Engineering:** * Automated handling of numerical and categorical data using `ColumnTransformer`.
    * Scaling of financial and behavioral metrics (Tenure, Monthly Charges).
* **Model Comparison:** Evaluating multiple classification algorithms, including:
    * **Logistic Regression:** For baseline interpretability.
    * **Random Forest & Gradient Boosting:** For capturing non-linear relationships.
* **Handling Class Imbalance:** Techniques to address the naturally skewed nature of churn data.
* **Performance Deep Dive:** Focus on **Recall** and **F1-Score** to ensure the model doesn't overlook customers likely to leave.

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Libraries:**
    * `Scikit-learn`: Pipeline construction, preprocessing, and classification.
    * `Pandas` & `NumPy`: For data cleaning and feature manipulation.
    * `Matplotlib` & `Seaborn`: For visualizing feature importance and churn correlations.
    * `Imbalanced-learn`: For balancing datasets.

## 📊 Analysis Workflow
1.  **Exploratory Data Analysis (EDA):** Identifying the "Churn Profile"—common traits among customers who cancel their services.
2.  **Preprocessing Pipeline:** Streamlining `StandardScaler` and `OneHotEncoder` to prevent data leakage.
3.  **Feature Importance:** Using tree-based models to rank which factors (e.g., contract type, paperless billing) drive churn most.
4.  **Hyperparameter Tuning:** Optimizing model parameters to maximize predictive accuracy.
5.  **Evaluation:** Comparing Baseline vs. Enhanced models to quantify the impact of feature engineering.

## 📂 Dataset
The project utilizes a **Customer Churn Dataset** (Telco style), featuring:
* **Demographics:** Gender, seniority, and partner status.
* **Service Details:** Phone service, multiple lines, internet provider, and tech support.
* **Account Info:** Tenure, contract type, payment method, and monthly charges.
* **Target:** `Churn` (Yes/No).

## 📖 How to Use
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/your-username/customer-churn-prediction.git](https://github.com/your-username/customer-churn-prediction.git)
    ```
2.  **Install Dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
    ```
3.  **Run the Notebook:**
    Open `feature_engineering_for_customer_churn_prediction.ipynb` in Google Colab or Jupyter Notebook to see the transformation steps and final model comparisons.

---
*Developed as part of a Data Science exploration into Feature Engineering and Customer Retention.*
