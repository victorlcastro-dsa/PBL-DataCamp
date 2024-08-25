
---

# 🚔 Analyzing Crime in Los Angeles

This [notebook](https://github.com/victorlcastro-dsa/PBL_DataCamp/blob/main/workspaces/analyzing_crime_in_los_angeles/workspace/notebook.ipynb) supports the Los Angeles Police Department (LAPD) by analyzing crime data to identify patterns in criminal behavior. The goal is to provide insights that can help the LAPD allocate resources more effectively to protect the citizens of Los Angeles.

## 📊 Dataset

The dataset used in this project, `crimes.csv`, is a modified version of the original data from Los Angeles Open Data. It includes the following columns:

| Column               | Description                                                                                             |
|----------------------|---------------------------------------------------------------------------------------------------------|
| `DR_NO`              | 📁 Division of Records Number: Official file number made up of a 2-digit year, area ID, and 5 digits.    |
| `Date Rptd`          | 📅 Date reported - MM/DD/YYYY.                                                                           |
| `DATE OCC`           | 📆 Date of occurrence - MM/DD/YYYY.                                                                      |
| `TIME OCC`           | ⏰ Time of occurrence in 24-hour military format.                                                        |
| `AREA NAME`          | 🌆 Geographic area or patrol division responsible for the location.                                      |
| `Crm Cd Desc`        | 📝 Description of the crime committed.                                                                   |
| `Vict Age`           | 🎂 Age of the victim.                                                                                    |
| `Vict Sex`           | 🚻 Gender of the victim (`F`: Female, `M`: Male, `X`: Unknown).                                          |
| `Vict Descent`       | 🌍 Descent or ethnic background of the victim.                                                           |
| `Weapon Desc`        | 🔪 Description of the weapon used, if applicable.                                                        |
| `Status Desc`        | 📜 Status of the crime.                                                                                  |
| `LOCATION`           | 🏢 Street address where the crime occurred.                                                              |

## 🎯 Objective

The primary objectives are:

- Identify the hour with the highest frequency of crimes.
- Determine the area with the largest frequency of night crimes (committed between 10 PM and 3:59 AM).
- Analyze the distribution of crimes against victims of different age groups.

## 🛠️ Instructions

1. **Dataset Loading**: Load the `crimes.csv` dataset.
2. **Data Exploration**: Explore the dataset to understand the distribution of crimes across various factors such as time, location, and victim demographics.
3. **Analysis**: Answer key questions about the timing and location of crimes, and the demographics of victims.
4. **Visualization**: Use visual tools like seaborn and matplotlib to illustrate findings.

## 📦 Dependencies

This notebook requires the following libraries:

- 🐼 pandas
- 📊 seaborn
- 🎨 matplotlib
- 🔢 numpy

## 🚀 Usage

To use this notebook, follow these steps:

1. **Clone the repository**.
2. **Install the necessary dependencies**.
3. **Open the notebook** in a compatible environment such as Jupyter.
4. **Run the cells** sequentially to perform the analysis and generate visualizations.

---

