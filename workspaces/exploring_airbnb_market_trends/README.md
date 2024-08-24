
---

# 🏙️ NYC Airbnb Market Analysis

This [notebook](https://github.com/victorlcastro-dsa/PBL_DataCamp/blob/651c8808c28cb00ce6c380119377d8ee6f1f523c/workspaces/exploring_airbnb_market_trends/workspace/notebook.ipynb) is designed to explore the short-term rental market in New York City by analyzing Airbnb listings. The project aims to provide insights into the market by combining data from various sources, including CSV, TSV, and Excel files.

## 📊 Dataset

The project uses three datasets containing information about Airbnb listings in New York City for the year 2019:

| File Name               | Description                                                                                   |
|-------------------------|-----------------------------------------------------------------------------------------------|
| `airbnb_price.csv`       | Contains data on listing prices and locations.                                                |
| `airbnb_room_type.xlsx`  | Contains data on listing descriptions and room types.                                         |
| `airbnb_last_review.tsv` | Contains data on host names and the dates of the last reviews.                                |

### Dataset Columns

| Column             | Description                                                                                           |
|--------------------|-------------------------------------------------------------------------------------------------------|
| `listing_id`       | 🔢 Unique identifier of the listing                                                                    |
| `price`            | 💵 Nightly listing price in USD                                                                        |
| `nbhood_full`      | 🏘️ Name of the borough and neighborhood where the listing is located                                  |
| `description`      | 📄 Listing description                                                                                 |
| `room_type`        | 🛏️ Type of room offered (shared room, private room, or entire home/apartment)                         |
| `host_name`        | 🙋‍♂️ Name of the listing host                                                                         |
| `last_review`      | 📅 Date when the listing was last reviewed                                                             |

## 🎯 Objective

As a consultant for a real estate start-up, the objective is to analyze the Airbnb data to provide valuable insights into the short-term rental market in New York City, with a focus on private rooms. The key tasks include:

1. **Review Analysis**: Determine the earliest and most recent review dates.
2. **Private Room Analysis**: Calculate the number of listings that are private rooms.
3. **Price Analysis**: Compute the average listing price.
4. **Data Combination**: Merge the data into a single DataFrame for analysis.

## 🏆 Key Findings

- The earliest and most recent review dates were identified.
- The number of private room listings was calculated.
- The average nightly listing price was computed and analyzed.
- A final DataFrame was created that consolidates the key variables for further analysis.

## 🛠️ Instructions

1. **Data Loading**: Load the datasets from CSV, TSV, and Excel files.
2. **Data Merging**: Merge the datasets on the `listing_id` to create a comprehensive DataFrame.
3. **Data Analysis**: Perform the required analysis to extract insights on review dates, room types, and prices.
4. **Result Compilation**: Combine the results into a single DataFrame for easy interpretation.

## 📦 Dependencies

This notebook requires the following Python libraries:

- 🐼 pandas
- 🧮 numpy

## 🚀 Usage

To use this notebook:

1. **Clone the repository** containing the notebook and datasets.
2. **Install the necessary dependencies** using `pip install -r requirements.txt`.
3. **Run the notebook** in Jupyter or any other compatible environment to perform the analysis.

---

