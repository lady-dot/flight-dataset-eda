**Exploratory Data Analysis: Airline Passengers Trend**
This repository contains a comprehensive Exploratory Data Analysis (EDA) of the famous flights dataset using Python. The project explores airline passenger growth from 1949 to 1960, identifying seasonal patterns and annual trends through various data visualization techniques.

📌 **Project Overview**
The goal of this project is to analyze the "Flights" dataset to understand:
 * The yearly growth of airline passengers.
 * Monthly seasonality and peak travel times.
 * Data distribution and summary statistics.

🛠️ **Tech Stack**
 * Python (Core Analysis)
 * Pandas: Data manipulation and aggregation.
 * Seaborn: High-level statistical data visualization.
 * Matplotlib: Underlying plotting engine for customizations.

📊 **Key Findings & Visualizations**
The analysis includes several key steps and visualizations:
 * Data Cleaning: Handled loading issues, checked for missing values (is_na), and confirmed no duplicate entries exist.
 * Statistical Summary: Used .describe() to identify passenger ranges (Min: 104, Max: 622).
 * Box Plots: Visualized the distribution of passengers per year, highlighting the clear upward trend in the aviation industry.
 * Heatmaps: Created a pivot table to map Months vs. Years, revealing that July and August are consistently the busiest months.
 * Violin Plots: Provided a deeper look into the distribution density of passengers across different months.
 * Time Series Analysis: Line plots showing the steady increase in travel demand over a decade.

🚀 **How to Run**
 * Clone this repository:
   git clone https://github.com/lady-dot/flights-dataset-eda.git

 * Install the required dependencies:
   pip install pandas seaborn matplotlib

 * Run the Jupyter Notebook or Python script to generate the plots.

📂 **Dataset**
The dataset used is the flights dataset from Seaborn. It contains three columns:
 * year: 1949 to 1960.
 * month: January to December.
 * passengers: Total count of passengers (in thousands).
If you found this analysis helpful, feel free to ⭐ the repo!
