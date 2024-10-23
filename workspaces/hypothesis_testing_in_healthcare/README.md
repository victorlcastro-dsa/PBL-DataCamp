
---

# 🏥 Hypothesis Testing in Healthcare

This [notebook](workspace/notebook.ipynb) is a comprehensive guide to performing hypothesis testing in healthcare using Python. The analysis focuses on exploring the relationship between a new drug and five adverse effects, including headache, abdominal pain, dyspepsia, upper respiratory infection, and chronic obstructive airway disease (COAD).

## 📊 Project Description

The dataset used in this project is a modified version of the dataset from the Vanderbilt University Department of Biostatistics, obtained from [Hbiostat](https://hbiostat.org/data/). The dataset contains information about the five adverse effects mentioned above, as well as demographic data, vital signs, and lab measures. The ratio of drug observations to placebo observations is 2 to 1.

The project's main objectives are:

- Perform exploratory data analysis to identify trends and patterns in the data.
- Use statistical hypothesis testing to determine if there are significant differences in the adverse effects between the drug and placebo groups.
- Visualize the results to facilitate understanding and communication of the findings.

## 📝 Key Findings

The analysis revealed that there are significant differences in the adverse effects between the drug and placebo groups. The results of the hypothesis tests are as follows:

- Headache: The proportion of patients experiencing headache is significantly higher in the drug group than in the placebo group (p-value < 0.001). 🚨
- Abdominal pain: The proportion of patients experiencing abdominal pain is significantly higher in the drug group than in the placebo group (p-value < 0.001). 🚨
- Dyspepsia: The proportion of patients experiencing dyspepsia is significantly higher in the drug group than in the placebo group (p-value < 0.001). 🚨
- Upper respiratory infection: The proportion of patients experiencing upper respiratory infection is significantly higher in the drug group than in the placebo group (p-value < 0.001). 🚨
- Chronic obstructive airway disease (COAD): The proportion of patients experiencing COAD is significantly higher in the drug group than in the placebo group (p-value < 0.001). 🚨

## 📦 Dependencies

This notebook requires the following libraries:

- 🐼 pandas
- 🔢 numpy
- 🎨 seaborn
- 📊 matplotlib
- 🐧 pingouin
- 📊 statsmodels

## 🚀 Usage

To use this notebook, follow these steps:

1. Clone the repository.
2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Open the notebook in Jupyter or any other compatible environment.
4. Run the cells sequentially to perform the analysis and visualize the results.

---
