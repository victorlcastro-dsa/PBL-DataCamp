
---

# 🌾 Predictive Modeling for Agriculture

This [notebook](https://github.com/victorlcastro-dsa/PBL_DataCamp/blob/3088ae3e5a1d3a68a0d82164620f72b47275f235/workspaces/predictive_modeling_for_agriculture/workspace/notebook.ipynb) is designed to assist farmers in selecting the best crop for their fields using supervised machine learning and feature selection techniques. The goal is to identify the single most important soil measure that can accurately predict the best crop to cultivate.

## 📊 Dataset

The dataset utilized in this analysis contains the following columns representing essential soil measures:

| Column              | Description                                                                                  |
|---------------------|----------------------------------------------------------------------------------------------|
| `Nitrogen`          | 🌱 Nitrogen content ratio in the soil                                                         |
| `Phosphorous`       | 🌾 Phosphorous content ratio in the soil                                                      |
| `Potassium`         | 🍃 Potassium content ratio in the soil                                                        |
| `pH`                | 🌍 pH value of the soil                                                                       |
| `Crop`              | 🌻 Target variable: the best crop to cultivate based on the soil's nutrient profile           |

## 🎯 Objective

The primary objective is to develop a machine learning model that can accurately predict the best crop for a field based on the most crucial soil measure. The model focuses on identifying the single soil measure that results in the highest prediction accuracy.

## 🏆 Key Findings

The best-performing feature identified in this analysis is `'K'`, with an accuracy of **0.138**.

## 🛠️ Instructions

1. **Dataset Preparation**: Load the provided dataset into the notebook.
2. **Data Exploration**: Perform exploratory data analysis (EDA) to understand the distribution and relationships among soil measures.
3. **Model Development**: Train and evaluate a machine learning model to predict the target variable.
4. **Feature Importance**: Identify and evaluate the impact of each soil measure on model performance.

## 📦 Dependencies

This notebook requires the following libraries:

- 🐼 pandas
- 📈 scikit-learn

## 🚀 Usage

To use this notebook, follow these steps:

1. **Clone the repository**.
2. **Install the necessary dependencies** using `pip install -r requirements.txt`.
3. **Open the notebook** in Jupyter or any other compatible environment.
4. **Run the cells** sequentially to perform the analysis and obtain results.

---