# 🌦️ Predicting Temperature in London

This [notebook](workspace/notebook.ipynb) is designed to build a machine learning pipeline for predicting the mean temperature in London, England. By experimenting with different regression models using `sklearn` and `mlflow`, the project aims to identify the best approach for predicting weather patterns.

## 📊 Dataset

The project utilizes the `london_weather.csv` dataset which contains the following columns:

- **date**: Recorded date of measurement (int)
- **cloud_cover**: Cloud cover measurement in oktas (float)
- **sunshine**: Sunshine measurement in hours (hrs) (float)
- **global_radiation**: Irradiance measurement in Watt per square meter (W/m²) (float)
- **max_temp**: Maximum temperature recorded in degrees Celsius (°C) (float)
- **mean_temp**: **Target** mean temperature in degrees Celsius (°C) (float)
- **min_temp**: Minimum temperature recorded in degrees Celsius (°C) (float)
- **precipitation**: Precipitation measurement in millimeters (mm) (float)

## 🎯 Objective

The primary objectives are:

- Run experiments to determine the best regression model for predicting mean temperature.
- Utilize a combination of `sklearn` and `mlflow` for model training and tracking.
- Analyze different weather factors to improve prediction accuracy.

## 🛠️ Instructions

1. **Data Preparation**: Load and explore the `london_weather.csv` dataset.
2. **Model Training**: Experiment with various regression models to predict the mean temperature.
3. **Model Evaluation**: Evaluate model performance and track results using `mlflow`.
4. **Optimization**: Fine-tune models to improve prediction accuracy.

## 📦 Dependencies

This notebook requires the following libraries:

- 🐍 Python 3.x
- 📓 Jupyter Notebook
- 📊 pandas
- 🔢 numpy
- 📈 scikit-learn
- 📊 mlflow

## 🚀 Usage

To use this notebook, follow these steps:

1. **Clone the repository**.
2. **Install the necessary dependencies** using `pip install -r requirements.txt`.
3. **Open the notebook** in Jupyter or any other compatible environment.
4. **Run the cells** sequentially to perform the analysis and obtain results.

---
