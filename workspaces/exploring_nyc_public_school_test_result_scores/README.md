
---

# 🏫 Exploring NYC Public School Test Result Scores

This [notebook] is designed to explore the standardized test performance across New York City's public schools. The project aims to provide insights into the SAT scores by examining math results, analyzing performance by borough, and identifying the top ten performing schools in the city.

## 📊 Dataset

The project uses a dataset containing information about NYC public schools' SAT scores:

| File Name         | Description                                                                                   |
|-------------------|-----------------------------------------------------------------------------------------------|
| `schools.csv`     | Contains data on school names, SAT scores, and borough information.                            |

### Dataset Columns

| Column             | Description                                                                                           |
|--------------------|-------------------------------------------------------------------------------------------------------|
| `school_name`      | 🏫 Name of the school                                                                                 |
| `average_math`     | 📐 Average SAT math score for the school                                                               |
| `average_reading`  | 📚 Average SAT reading score for the school                                                            |
| `average_writing`  | ✍️ Average SAT writing score for the school                                                            |
| `borough`          | 🗺️ Borough where the school is located                                                                |

## 🎯 Objective

The objective is to analyze the SAT performance of NYC public schools and provide insights into the following areas:

1. **Top Math Performers**: Identify the schools with the best math results, where the scores are at least 80% of the maximum possible score (800 points).
2. **Performance by Borough**: Analyze how SAT performance varies by borough.
3. **Top 10 Schools**: Rank the top ten schools based on their combined SAT scores.

## 🏆 Key Findings

- Schools with the highest math scores were identified.
- Variations in SAT performance across different boroughs were analyzed.
- The top ten schools based on combined SAT scores were ranked and listed.

## 🛠️ Instructions

1. **Data Loading**: Load the dataset from the `schools.csv` file.
2. **Data Analysis**: Perform analysis to identify top math performers, analyze borough performance, and rank schools based on combined SAT scores.
3. **Result Compilation**: Compile the results into a DataFrame for easy interpretation.

## 📦 Dependencies

This notebook requires the following Python libraries:

- 🐼 pandas
- 📊 matplotlib (for visualizations, if applicable)

## 🚀 Usage

To use this notebook:

1. **Clone the repository** containing the notebook and dataset.
2. **Install the necessary dependencies** using `pip install pandas matplotlib`.
3. **Run the notebook** in Jupyter or any other compatible environment to perform the analysis.

---

