# Used Cars Data Visualization Exercise 🚗

## Project Overview
This project is a foundational exercise in data visualization using Python. It demonstrates how to load a real-world dataset and generate fundamental charts to visually summarize and understand the data using Pandas and Matplotlib.

## Dataset
* **Source File:** `used_cars.csv`
* **Size:** 4,009 records
* **Key Features Displayed:** `price`, `fuel_type`, `transmission`, `milage`, `brand`

## Tech Stack
* **Language:** Python
* **Data Handling:** Pandas
* **Data Visualization:** Matplotlib

## Visualizations Built
The notebook includes scripts to generate the following standard chart types:
1. **Histogram:** To view the frequency distribution of car prices.
2. **Pie Chart:** To visualize the percentage breakdown of different fuel types.
3. **Bar Charts:** To compare categorical counts (e.g., Transmission types) and calculate basic aggregations (e.g., Average price per car brand).
4. **Scatter Plot:** To map the basic relationship between continuous numerical variables (Mileage vs. Price).

## How to Run

### Option 1: Run in Cloud (Recommended)
You can view and run this notebook instantly in your browser using Google Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ronanpatrick/used-cars-eda/blob/main/Used_Cars_Data_Visualization.ipynb.ipynb)

*(Note: If running in Colab, you will need to manually upload the `used_cars.csv` file to your session storage, or update the `pd.read_csv()` path to point to the raw GitHub URL of the dataset).*

### Option 2: Run Locally
1. Clone this repository: `git clone https://github.com/ronanpatrick/used-cars-eda.git`
2. Ensure you have Jupyter Notebook or VS Code installed.
3. Install the required libraries: `pip install pandas matplotlib`
4. Open the `.ipynb` file and run the cells. The dataset is loaded via a local relative path.
