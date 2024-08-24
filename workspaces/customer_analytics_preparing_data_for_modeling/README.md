
---

# 📊 Customer Analytics: Preparing Data for Modeling

This [notebook](https://github.com/victorlcastro-dsa/PBL_DataCamp/blob/main/workspaces/customer_analytics_preparing_data_for_modeling/workspace/hr-image-small.png) was created to assist *Training Data Ltd.* in optimizing the storage of a large customer dataset, which will be used to predict whether students are looking for a new job. The goal is to apply optimization techniques to ensure that the machine learning model can process the data more efficiently, reducing the time required to generate predictions.

## 📊 Dataset

The dataset used in this project is provided as `customer_train.csv` and contains the following columns:

| Column                  | Description                                                                                  |
|-------------------------|----------------------------------------------------------------------------------------------|
| `student_id`            | 🔢 Unique identifier for each student.                                                       |
| `city`                  | 🌆 Code for the city where the student lives.                                                |
| `city_development_index`| 🌍 Scaled development index for the city.                                                    |
| `gender`                | 🚻 The student's gender.                                                                     |
| `relevant_experience`   | 💼 Indicator of whether the student has relevant work experience.                            |
| `enrolled_university`   | 🎓 Type of university course enrolled in (if any).                                           |
| `education_level`       | 📚 The student's education level.                                                            |
| `major_discipline`      | 📖 The student's major discipline.                                                           |
| `experience`            | ⏳ Years of work experience.                                                                 |
| `company_size`          | 🏢 Size of the company where the student works/worked.                                        |
| `company_type`          | 🏭 Type of company.                                                                          |
| `last_new_job`          | 🔄 Time since the last job.                                                                  |
| `training_hours`        | ⏱️ Number of training hours.                                                                 |
| `target`                | 🎯 Target variable: whether the student was looking for a new job during the training (`0`: No, `1`: Yes). |

## 🎯 Objective

The primary objective is to transform the dataset into a more efficient format by applying the following optimizations:

- **Booleans** for columns with binary categories.
- **32-bit integers** for columns that contain only integer values.
- **16-bit floats** for continuous numerical columns.
- **Categorical** for nominal categorical columns.
- **Ordered Categories** for ordinal categorical columns.

## 🏆 Key Findings

The transformation resulted in a substantial reduction in memory usage, making data processing more efficient for predictive models.

## 🛠️ Instructions

1. **Dataset Preparation**: Load the `customer_train.csv` dataset.
2. **Data Exploration**: Explore and identify categorical and ordinal columns.
3. **Data Transformation**: Apply storage optimizations as specified.
4. **Evaluation**: Compare memory usage before and after the transformation.

## 📦 Dependencies

This notebook requires the following libraries:

- 🐼 pandas

## 🚀 Usage

To use this notebook, follow these steps:

1. **Clone the repository**.
2. **Install the necessary dependencies**.
3. **Open the notebook** in a compatible environment such as Jupyter.
4. **Run the cells** sequentially to perform the analysis.

---

