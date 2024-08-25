
---

# 🛡️ Insurance Claims Prediction

This [notebook](https://github.com/victorlcastro-dsa/PBL_DataCamp/blob/3088ae3e5a1d3a68a0d82164620f72b47275f235/workspaces/modeling_car_insurance_claim_outcomes/workspace/notebook.ipynb) is designed to assist insurance companies in predicting whether a customer will make a claim on their car insurance during the policy period. The goal is to identify the single most important feature that results in the best model accuracy.

## 📊 Dataset

The dataset used in this analysis is provided as `car_insurance.csv` and contains the following columns:

| Column             | Description                                                                                            |
|--------------------|--------------------------------------------------------------------------------------------------------|
| `id`               | 🔢 Unique client identifier                                                                            |
| `age`              | 🎂 Client's age (categorized)                                                                          |
| `gender`           | 🚻 Client's gender                                                                                     |
| `driving_experience` | 🚗 Years the client has been driving (categorized)                                                   |
| `education`        | 🎓 Client's level of education                                                                         |
| `income`           | 💰 Client's income level                                                                               |
| `credit_score`     | 💳 Client's credit score (between 0 and 1)                                                             |
| `vehicle_ownership` | 🚙 Whether the client owns a vehicle (`0`: No, `1`: Yes)                                              |
| `marital_status`   | 💍 Client's marital status                                                                             |
| `vehicle_type`     | 🚘 Type of vehicle owned (`0`: Utility, `1`: Luxury)                                                   |
| `annual_mileage`   | 📏 Estimated annual mileage driven by the client                                                       |
| `policy_claim`     | 📋 Target variable: whether the client made a claim during the policy period (`0`: No, `1`: Yes)       |

## 🎯 Objective

The main objective is to develop a machine learning model that can accurately predict whether a customer will file a claim during the policy period. The model focuses on identifying the single feature that leads to the best accuracy.

## 🏆 Key Findings

The best-performing feature identified in this analysis is `driving_experience`, with an accuracy of **77.71%**.

## 🛠️ Instructions

1. **Dataset Preparation**: Load the `car_insurance.csv` dataset.
2. **Data Exploration**: Explore and preprocess the data.
3. **Model Development**: Train and evaluate a machine learning model to predict the target variable `policy_claim`.
4. **Feature Importance**: Identify and evaluate the impact of each feature on model performance.

## 📦 Dependencies

This notebook requires the following libraries:

- 🐼 pandas
- 🧮 numpy
- 📈 scikit-learn
- 🎨 matplotlib

## 🚀 Usage

To use this notebook, follow these steps:

1. **Clone the repository**.
2. **Install the necessary dependencies**.
3. **Open the notebook** in Jupyter or any other compatible environment.
4. **Run the cells** sequentially to perform the analysis.

---