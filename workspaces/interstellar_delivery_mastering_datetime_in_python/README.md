
---

# 🚀 Interstellar Delivery: Mastering Datetime in Python

This [notebook](workspace/notebook.ipynb) was developed to help build reusable Python functions that are crucial for an intergalactic logistics startup. The main focus is on manipulating dates and times using Python's `datetime` module, essential for managing space deliveries.

## 🎯 Objective

The main objective is to develop functions that can:

- **Format timestamps**: Convert Unix timestamps into human-readable date and time strings.
- **Calculate landing times**: Estimate rocket landing times based on launch time and travel duration.
- **Determine delivery deadlines**: Calculate the number of days remaining until the expected delivery date.

## 🛠️ Key Functions

The project includes the following key functions:

1. **`format_date()`**:
   - Converts a Unix timestamp into a formatted date-time string.
   - Example: `format_date(1634078400, "%Y-%m-%d %H:%M:%S")` returns `2021-10-13 12:00:00`.

2. **`calculate_landing_time()`**:
   - Estimates the landing date and time of a rocket based on launch time and travel duration.
   - Returns: Landing date-time as a string.

3. **`days_until_delivery()`**:
   - Calculates the number of days remaining until the expected delivery date.
   - Returns: Number of days until delivery.

## 📦 Dependencies

This notebook requires the following libraries:

- 🐍 Python 3.x
- 📓 Jupyter Notebook
- ⌚ datetime (standard Python module)

## 🚀 Usage

To use this notebook, follow these steps:

1. **Clone the repository**.
2. **Install the necessary dependencies**.
3. **Open the notebook** in Jupyter or any other compatible environment.
4. **Run the cells** sequentially to perform the analysis.

---
