
---

# 🐱 Mobile Games A/B Testing with Cookie Cats

This [notebook](https://github.com/victorlcastro-dsa/PBL_DataCamp/blob/4133664f5fdf851049661749d3e46c01d358641f/workspaces/mobile_games_a_b_testing_with_cookie_cats/workspace/notebook.ipynb) examines an A/B test conducted in the popular mobile puzzle game, *Cookie Cats*. The goal of the analysis is to understand the impact of moving a gameplay gate from level 30 to level 40 on player retention.

## 🎮 Project Description

*Cookie Cats* is a widely popular mobile game developed by Tactile Entertainment. It follows the classic "connect three" puzzle style, where players match tiles of the same color to clear levels. The game also features singing cats, adding a unique charm to the gameplay.

During the game, players encounter gates that either require waiting or making an in-app purchase to continue playing. These gates serve to encourage purchases and give players a break, potentially increasing their long-term enjoyment.

This project analyzes an A/B test where the first gate was moved from level 30 to level 40 to observe its effect on player retention. We investigate whether this change impacts 1-day and 7-day retention rates.

## 📊 Dataset

The dataset for this project includes information about player behavior before and after the gate was moved. Key columns include:

| Column             | Description                                                                                  |
|--------------------|----------------------------------------------------------------------------------------------|
| `userid`           | Unique identifier for each player.                                                           |
| `version`          | Indicates whether the player experienced the gate at level 30 or level 40.                   |
| `sum_gamerounds`   | Total number of game rounds played by the player during the first week.                      |
| `retention_1`      | Whether the player returned to the game 1 day after installation.                            |
| `retention_7`      | Whether the player returned to the game 7 days after installation.                           |

## 🎯 Objective

The primary objectives are:

- Assess the impact of moving the gate on 1-day and 7-day player retention.
- Determine which gate position (level 30 or level 40) results in higher retention rates.
- Provide recommendations for game developers based on the analysis.

## 🛠️ Instructions

1. **Data Loading**: Load the dataset and familiarize yourself with its structure.
2. **Exploratory Data Analysis**: Analyze the data to identify patterns in player behavior related to the gate's position.
3. **Hypothesis Testing**: Conduct hypothesis tests and bootstrap analysis to evaluate retention differences between the two versions.
4. **Visualization**: Use visualizations to illustrate retention rates and other relevant metrics.

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

